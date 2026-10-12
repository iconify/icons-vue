<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tha879byy"/><path class="klrsj1bkw"/><path class="mnuzy7u_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fleet-tracking" /></template>
<style>
.klrsj1bkw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.75h.01");
}

.mnuzy7u_g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12.25a2 2 0 0 1 2 2c0 2.61-2 4.75-2 4.75s-2-2.14-2-4.75a2 2 0 0 1 2-2m14.5 0a2 2 0 0 1 2 2c0 2.61-2 4.75-2 4.75s-2-2.14-2-4.75a2 2 0 0 1 2-2m-16.5 9h18.5");
}

.tha879byy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a5 5 0 0 1 5 5c0 4.5-5 8.5-5 8.5s-5-4-5-8.5a5 5 0 0 1 5-5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
