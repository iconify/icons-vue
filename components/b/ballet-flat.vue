<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ob_h2lbta"/><path class="owpy-pgkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ballet-flat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ob_h2lbta {
  d: path("M2.75 17.75V13q0-1 1-.75c1.75 1.5 5.75 2 9.25 1c4-.5 8.25 2 8.25 4.25q0 1.25-1.25 1.25H3.75q-1 0-1-1");
}

.owpy-pgkv {
  d: path("M7 13.75c1-3.5 4.5-3.75 5.75-.4");
}

</style>
