<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="el753yuux"/><path class="fb4zxqney"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blob-outline-thin" /></template>
<style>
.el753yuux {
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.fb4zxqney {
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
