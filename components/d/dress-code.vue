<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rqiqv_bly"/><path class="f9loc6b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dress-code" /></template>
<style>
.f9loc6b5o {
  d: path("m8 3l4 4l4-4m-5 4h2l1 8l-2 2.5l-2-2.5Z");
}

.rqiqv_bly {
  d: path("M8 3L3.5 5.5l-1 5.5L6 12v9h12v-9l3.5-1l-1-5.5L16 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
