<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ozjblsbwb"/><path class="qns7l7biu"/><path class="egedvw93v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dolphin" /></template>
<style>
.egedvw93v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 9.75h.01");
}

.ozjblsbwb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 18.25C6 12 10.5 7.5 15.5 7.5c2.25 0 4 1.25 5 3l.75 1.5h-3.5C12.5 12 8 15 6 19.25Zm.75.5L3 17.5m2.25 1.25l.25 2.5");
}

.qns7l7biu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9.5l-.75-4.25C10.5 5.5 12 6.25 13 7.5c-1.25.4-2.4 1.05-3.5 2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
