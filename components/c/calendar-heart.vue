<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="si_c6-wrh"/><path class="i7l0ccctm"/><path class="ojudzkb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-heart" /></template>
<style>
.i7l0ccctm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M8 17h.01");
}

.ojudzkb0y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 21c-.2 0-.4-.07-.55-.2c-1.65-1.4-3.7-3.05-3.7-5.3c0-1.3 1-2.35 2.25-2.35c.8 0 1.5.4 2 1.1c.5-.7 1.2-1.1 2-1.1c1.25 0 2.25 1.05 2.25 2.35c0 2.25-2.05 3.9-3.7 5.3c-.15.13-.35.2-.55.2");
}

.si_c6-wrh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 20.25h-5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v3.5M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
