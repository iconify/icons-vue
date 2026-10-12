<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="roz3qacxy"/><path class="opapsacfn"/><path class="np225_bxb"/><path class="h365r_ndt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gorilla" /></template>
<style>
.h365r_ndt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 15h2");
}

.np225_bxb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 12h.01m2.99 0h.01");
}

.opapsacfn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10.75C8.5 10 9 9.5 9.75 9.5h4.5c.75 0 1.25.5 1.25 1.25c0 .5-.25 1-.5 1.25c.75.75 1 1.5 1 2.5c0 1.75-1.5 3-3.75 3s-4-1.25-4-3c0-1 .25-1.75 1-2.5c-.5-.25-.75-.75-.75-1.25");
}

.roz3qacxy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c4.5 0 7.5 3.25 7.5 7.75v3c0 4-3.25 6.75-7.5 6.75S4.5 18 4.5 14v-3c0-4.5 3-7.75 7.5-7.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
