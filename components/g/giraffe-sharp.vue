<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b4jr0bldo"/><path class="o9-qq1b-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:giraffe-sharp" /></template>
<style>
.b4jr0bldo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 21.25L8.5 9l.511-3.75H13.5l5.85 2.2l2.281.869L19.95 10l-.895.895L17.9 10.4l-4.65-1.9L11 21.25Zm4.25-16v-2.5m2.75 2.75V2.75");
}

.o9-qq1b-a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.5h.01M9.5 17h.01m4.74-9.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
