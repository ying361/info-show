<template>
  <div class="header-menu">
    <el-menu mode="horizontal">
      <el-menu-item>菜单一</el-menu-item>
      <el-menu-item>菜单二</el-menu-item>
      <el-menu-item>菜单三</el-menu-item>
    </el-menu>
    <!-- <div class="sj">111</div> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HeaderMenu',
  components: {
  },
})
</script>
<style lang="scss" scoped>
.sj {
  width:0;
  height:0;
  border:10px solid transparent;
  border-top:10px solid #cc4646;
}
</style>
