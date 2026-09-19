<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zi-2cyd-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3drop" /></template>
<style>
.zi-2cyd-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5s11.482 21.864 11.914 23.474A12.333 12.333 0 0 1 16.925 41.27a12.33 12.33 0 0 1-4.839-13.295C12.605 26.04 24 4.5 24 4.5m0 0l12.022 29.424");
}

</style>
