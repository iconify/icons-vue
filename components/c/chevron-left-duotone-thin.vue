<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kafa4eb3l"/><path class="fbschg62a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-left-duotone-thin" /></template>
<style>
.fbschg62a {
  d: path("m15 5 -7 7 7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kafa4eb3l {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
