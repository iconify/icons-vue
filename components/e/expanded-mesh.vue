<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqgbm28pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:expanded-mesh" /></template>
<style>
.kqgbm28pd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 6h12.75A2.625 2.625 0 0 1 21 8.625v6.75A2.625 2.625 0 0 1 18.375 18H5.625A2.625 2.625 0 0 1 3 15.375v-6.75A2.625 2.625 0 0 1 5.625 6M3 9l9 9M6 6l12 12M12 6l9 9M3 15l9-9M6 18L18 6m-6 12l9-9");
}

</style>
