<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="b3t9tue6c"/><path class="sci58wslm"/><path class="s_4lyvmwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:city-hall" /></template>
<style>
.b3t9tue6c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V13a1 1 0 0 1 1-1H9V8a3 3 0 0 1 6 0v4h5.25a1 1 0 0 1 1 1v8.25ZM12 5V2.75");
}

.s_4lyvmwu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15.5V18m12.5-2.5V18m-7.75 3.25v-3.5h3v3.5");
}

.sci58wslm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
