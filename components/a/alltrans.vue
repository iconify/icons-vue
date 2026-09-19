<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nad2zibbm"/><path class="yusg0ty2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alltrans" /></template>
<style>
.nad2zibbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 43.5c2.2 0 4-1.8 4-4v-31c0-2.2-1.8-4-4-4h-23c-2.2 0-4 1.8-4 4v27.2a7.8 7.8 0 0 0 7.8 7.8z");
}

.yusg0ty2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 33.5L30 18l-5.3 15.5m1.8-5.2h6.8M13 18.7h13.6m-6.8-4.2c0 7.6-.2 9.1-6.1 15.2m10.2-2.9c-1.5-1.5-3.8-4.9-4.1-7.8");
}

</style>
