<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a9xbaebdi"/><path class="ngdi4achx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cylinder" /></template>
<style>
.a9xbaebdi {
  d: path("M3.5 6v12a8.5 3.25 0 0 0 17 0V6a8.5 3.25 0 0 1-17 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ngdi4achx {
  d: path("M3.5 6a8.5 3.25 0 1 0 17 0a8.5 3.25 0 1 0-17 0");
}

</style>
