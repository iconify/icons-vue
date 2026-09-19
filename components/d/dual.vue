<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u0j9w9bxh"/><path class="m2tforubt"/><path class="p6jm3nh6l"/><path class="ypzu7xa8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dual" /></template>
<style>
.m2tforubt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.244 4.177l7.406 7.406c.903.902.904 2.354.003 3.255L14.838 31.653c-.895.899-2.35.9-3.248.005l-.007-.007l-7.405-7.407a2.297 2.297 0 0 1-.01-3.248l.007-.007L20.989 4.175c.895-.898 2.35-.9 3.248-.005zm12.172 12.172l7.407 7.407c.902.902.903 2.354.002 3.255L27.01 43.825c-.896.898-2.35.9-3.249.005l-.007-.007l-7.406-7.407a2.297 2.297 0 0 1-.01-3.248l.008-.007L33.16 16.347c.896-.899 2.35-.9 3.249-.005z");
}

.p6jm3nh6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.866 18.462l7.845 7.844L26.306 41.71l-7.845-7.845zm-19.299-.554l2.876 1.66l-1.662 2.875l-2.873-1.66z");
}

.u0j9w9bxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.694 6.289l7.844 7.845l-15.404 15.404l-7.845-7.844z");
}

.ypzu7xa8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.392 24.061l2.876 1.661l-1.66 2.875l-2.876-1.66zm-12.394-6.036l1.215.701l-.701 1.216l-1.215-.702z");
}

</style>
