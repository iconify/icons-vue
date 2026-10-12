<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jjynuk-md"/><path class="x8232_bgk"/><path class="yw3eho_ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chalet" /></template>
<style>
.jjynuk-md {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.22 11.13l8.31-6.51q.47-.37.94 0l8.31 6.51q.47.37-.13.37H19.1q-.6 0-.6.6v8.55q0 .6-.6.6H6.1q-.6 0-.6-.6V12.1q0-.6-.6-.6H3.35q-.6 0-.13-.37m.53 4.12h16.5");
}

.x8232_bgk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yw3eho_ht {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-3h3v3");
}

</style>
