<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="whr1dbc1c"/><path class="uk1dv8bez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eid-calendar" /></template>
<style>
.uk1dv8bez {
  d: path("M13 12a3.5 3.5 0 1 0 0 6a4 4 0 0 1 0-6Zm3.5 1.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.whr1dbc1c {
  d: path("M3 4h18v17.5H3Zm5-1.5V6m8-3.5V6M3 8.5h18");
}

</style>
