<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dt85cu8ot"/><path class="s6n7q9bhe"/><path class="xe_dexb2m"/><path class="j-lv2ccaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dolphin-jump" /></template>
<style>
.dt85cu8ot {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 17c1.5-7.5 7.25-11.5 13-10.25c1.75.4 3.25 1.6 4 3.25c-.75.25-1.75.25-2.75 0c-4.75-.5-9.5 2-11.75 8.25L8 20.75L3.5 20Z");
}

.j-lv2ccaw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 20.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75S18.75 20 20 20");
}

.s6n7q9bhe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.25 8.5l.5-3.5l2.5 1.75");
}

.xe_dexb2m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 8.4h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
