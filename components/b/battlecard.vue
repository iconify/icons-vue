<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwdha7bjd"/><path class="cd-xd5qdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battlecard" /></template>
<style>
.cd-xd5qdg {
  d: path("M12.5 5.5H17A3.5 3.5 0 0 1 20.5 9v8.5A3.5 3.5 0 0 1 17 21h-4.5A3.5 3.5 0 0 1 9 17.5V9a3.5 3.5 0 0 1 3.5-3.5m-.25 4.5h5");
}

.gwdha7bjd {
  d: path("m9 18.5l-3.75.75L2 4.75l9.75-2.25l.75 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
