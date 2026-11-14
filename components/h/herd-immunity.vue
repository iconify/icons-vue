<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rh4hqugip"/><path class="o_786mfgw"/><path class="d5384e0bg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:herd-immunity" /></template>
<style>
.d5384e0bg {
  d: path("M5 15.75c.25-1.25 1-2 2-2c.75 0 1.5.35 2 .75m10 1.25c-.25-1.25-1-2-2-2c-.75 0-1.5.35-2 .75");
}

.o_786mfgw {
  d: path("M10 7.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7.75 18c0-2.75 1.75-4.75 4.25-4.75s4.25 2 4.25 4.75M5 10a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 5 10Zm10.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.rh4hqugip {
  d: path("M2 12a10 10 0 1 0 20 0a10 10 0 1 0-20 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
