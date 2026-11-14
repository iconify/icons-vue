<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l672kbbzs"/><path class="ouve24z0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esim-off" /></template>
<style>
.l672kbbzs {
  d: path("M6.4 2.5h8.1L19 7v8.036M17.564 21.5H5V8.964");
}

.ouve24z0u {
  d: path("M12.9 9h2.6v2.6M13.1 17H8.5v-4.6m-5-8.9l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
