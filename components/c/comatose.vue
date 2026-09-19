<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_hzh4s0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:comatose" /></template>
<style>
.w_hzh4s0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 13.3c0-3.9 1.1-7.6 2.9-10.8H24C12.1 2.5 2.5 12.1 2.5 24S12.1 45.5 24 45.5c8 0 14.9-4.3 18.6-10.7C31.2 34.3 22 24.9 22 13.3");
}

</style>
