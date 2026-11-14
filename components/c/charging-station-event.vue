<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfenysb5q"/><path class="kupkpf_fy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charging-station-event" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kupkpf_fy {
  d: path("m11.42 8.282l-1.995 2.882a.851.851 0 0 0 .7 1.336a1.418 1.418 0 0 1 1.405 1.61l-.155 1.14a.665.665 0 0 0 1.205.468l1.995-2.882a.851.851 0 0 0-.7-1.336a1.418 1.418 0 0 1-1.405-1.61l.155-1.14a.665.665 0 0 0-1.205-.468");
}

.rfenysb5q {
  d: path("M9.875 2.5h4.25A4.375 4.375 0 0 1 18.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 17.125V6.875A4.375 4.375 0 0 1 9.875 2.5");
}

</style>
