<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcqb0nbbi"/><path class="idd--tbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bluebell" /></template>
<style>
.hcqb0nbbi {
  d: path("M4 21.5C4 12 6.5 4 12.5 4C16 4 18 5.5 18 8m-8-3.5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idd--tbty {
  d: path("M18 8c-2 0-2 1.5-2 3.5l-.5 2h5l-.5-2c0-2 0-3.5-2-3.5m-8 .5C8 8.5 8 10 8 12l-.5 2h5l-.5-2c0-2 0-3.5-2-3.5");
}

</style>
