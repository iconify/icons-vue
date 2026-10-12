<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w-mgr6iyu"/><path class="lf-yftbhc"/><path class="cg77_l6fw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lucky-charm" /></template>
<style>
.cg77_l6fw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.75q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

.lf-yftbhc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.89 8.53h.01m2.85-3.41h.01m6.49 0h.01m2.85 3.41h.01");
}

.w-mgr6iyu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.75a8 8 0 0 1 16 0V20a1.25 1.25 0 0 1-1.25 1.25h-.5A1.25 1.25 0 0 1 17 20v-9.25a5 5 0 0 0-10 0V20a1.25 1.25 0 0 1-1.25 1.25h-.5A1.25 1.25 0 0 1 4 20Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
