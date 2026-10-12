<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kw3d5ct-r"/><path class="ncq0ct0me"/><path class="p_yljupba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-note" /></template>
<style>
.kw3d5ct-r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 20.25h-5.5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v3M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.ncq0ct0me {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01m3.24 0h.01M8 17.25h.01");
}

.p_yljupba {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 14.25h4q.75 0 .75.75v2q0 .75-.53 1.28l-1.44 1.44q-.53.53-1.28.53h-1.5q-.75 0-.75-.75V15q0-.75.75-.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
