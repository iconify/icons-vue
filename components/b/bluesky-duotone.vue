<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mfdk0mbmx"/><path class="o9so35bve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bluesky-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mfdk0mbmx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.6 13.3l.425.3c2.2 1.545 3.855 2.708 1.975 4.57c-.585.579-1.52 1.429-2.4 1.43c-1.8 0-2.82-2.49-3.15-3.15c-.25-.6-.3-1.05-.45-1.35c-.15.3-.2.75-.45 1.35c-.33.66-1.35 3.15-3.15 3.15c-.88-.001-1.815-.851-2.4-1.43c-1.88-1.862-.225-3.025 1.975-4.57l.425-.3c-1.983.323-4.243.131-4.9-2.13c-.19-.64-.5-4.57-.5-5.1c.002-2.717 2.511-1.746 3.9-.74c2.07 1.5 4.29 4.54 5.1 6.17c.81-1.63 3.03-4.67 5.1-6.17c1.389-1.006 3.898-1.977 3.9.74c0 .53-.32 4.46-.5 5.1c-.657 2.261-2.917 2.453-4.9 2.13");
}

.o9so35bve {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.4 13.3C6 15 4 16.19 6 18.17c.93.92 1.72 1.43 2.4 1.43c1.8 0 2.82-2.49 3.15-3.15c.25-.6.3-1.05.45-1.35c.15.3.2.75.45 1.35c.33.66 1.35 3.15 3.15 3.15c.68 0 1.47-.51 2.4-1.43c2-1.98 0-3.17-2.4-4.87m0 0c2.08.34 4.26.08 4.9-2.13c.18-.64.5-4.57.5-5.1c0-2.65-2.41-1.82-3.9-.74c-2.07 1.5-4.29 4.54-5.1 6.17c-.81-1.63-3.03-4.67-5.1-6.17C5.41 4.25 3 3.42 3 6.07c0 .53.31 4.46.5 5.1c.64 2.21 2.82 2.47 4.9 2.13");
}

</style>
