<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zc7hhleka"/><path class="p8aty-yxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dr-tv" /></template>
<style>
.p8aty-yxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34 24l-16-9.238v18.476z");
}

.zc7hhleka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 8.797c8.397-8.396 22.01-8.396 30.406 0s8.396 22.01 0 30.406s-22.01 8.396-30.406 0");
}

</style>
