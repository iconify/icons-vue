<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cyh5v_bnd"/><path class="rvy044akg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:funnel-stages" /></template>
<style>
.cyh5v_bnd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.5h16.5q.75 0 .26.56l-6.02 6.88q-.49.56-.49 1.31v3.5q0 .75-.75.75h-2.5q-.75 0-.75-.75v-3.5q0-.75-.49-1.31L3.49 5.06Q3 4.5 3.75 4.5m2.75 4h11");
}

.rvy044akg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
