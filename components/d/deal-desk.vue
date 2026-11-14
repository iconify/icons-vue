<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m5p-9ugry"/><path class="qr1h80hoo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deal-desk" /></template>
<style>
.m5p-9ugry {
  d: path("M11.7 16.5H2.5v-13h19v10.1M12 19.9v.6m-4 0h4.6");
}

.qr1h80hoo {
  d: path("M14.5 14.5h4l3.25 3.25l-4 4l-3.25-3.25Zm2.25 2.25h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
