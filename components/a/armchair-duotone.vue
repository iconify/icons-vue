<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uqdj3nbug"/><path class="p52avlbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p52avlbbf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11v5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-5a2 2 0 1 0-4 0a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2a2 2 0 1 0-4 0m2 7v2m12-2v2M6 9V6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v3");
}

.uqdj3nbug {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 12h4a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 21 11v5a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-5a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1");
}

</style>
