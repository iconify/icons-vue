<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rcct9ubga"/><path class="yo41v-bom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-organ" /></template>
<style>
.rcct9ubga {
  d: path("M15 15H2.5V3h19v8.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yo41v-bom {
  d: path("M7 3v6.5h3V3M8.5 9.5V15m5-12v6.5h3V3M15 9.5V15m4.75-1l-3.25 3.5h4L17.25 21");
}

</style>
