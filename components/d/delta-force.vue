<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wm9p3xbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:delta-force" /></template>
<style>
.wm9p3xbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.745 34.569l7.64-6.992h-6.392l7.365-11.97l13.791 24.54H5.851L24 7.853");
}

</style>
