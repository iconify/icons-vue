<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="njya-bkfw"/><path class="axu9m_tsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-ring-sharp-duotone" /></template>
<style>
.axu9m_tsl {
  d: path("M9.7679 19.134C10.6252 20.6188 11.2855 21 12 21C12.7145 21 13.3748 20.6188 14.2321 19.134M21 8.0117L21 8C21 6.22 20.4722 4.48 19.4833 3L19.1864 2.5556M3 8.0117L3 8C3 6.22 3.5278 4.48 4.5167 3L4.8136 2.5556");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.njya-bkfw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 17L5 17C4.4477 17 4 16.5523 4 16L4 15C4 14.4387 4.2784 13.9674 4.455 13.673C4.6689 13.3166 4.8785 13.007 5.1056 12.5528C5.5331 11.6977 6 10.3517 6 8C6 4.8244 8.8244 2 12 2C15.1756 2 18 4.8244 18 8C18 10.3517 18.4669 11.6977 18.8944 12.5528C19.1215 13.007 19.3311 13.3166 19.545 13.673C19.7216 13.9674 20 14.4387 20 15L20 16C20 16.5523 19.5523 17 19 17Z");
  stroke: none;
}

</style>
