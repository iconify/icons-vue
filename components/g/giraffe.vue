<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hn0e-sbea"/><path class="o9-qq1b-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:giraffe" /></template>
<style>
.hn0e-sbea {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 21.25L8.5 9c.3-2.2 2-3.75 4.25-3.75h.75l5.85 2.2c1.05.4 1.4 1.75.6 2.55c-.55.55-1.35.7-2.05.4l-4.65-1.9L11 21.25Zm4.25-16v-2.5m2.75 2.75V2.75");
}

.o9-qq1b-a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.5h.01M9.5 17h.01m4.74-9.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
