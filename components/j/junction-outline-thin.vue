<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7mb9vbwf"/><path class="x_6spmb5u"/><path class="cfwe2fbcx"/><path class="gaonsmbbz"/><path class="v3qgglbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:junction-outline-thin" /></template>
<style>
.cfwe2fbcx {
  d: path("M8 22v-6H2");
}

.gaonsmbbz {
  d: path("M16 22v-6h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7mb9vbwf {
  d: path("M8 2v6H2");
}

.v3qgglbcl {
  d: path("M12 9.5v5");
}

.x_6spmb5u {
  d: path("M16 2v6h6");
}

</style>
