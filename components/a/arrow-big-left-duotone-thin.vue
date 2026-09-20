<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r4vbc_6fl"/><path class="cq4cz2bia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-big-left-duotone-thin" /></template>
<style>
.cq4cz2bia {
  d: path("m3 12 9 -9v5h9v8h-9v5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r4vbc_6fl {
  fill: currentColor;
  d: path("m3 12 9 -9v5h9v8h-9v5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
