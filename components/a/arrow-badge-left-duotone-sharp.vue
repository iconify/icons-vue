<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u-y-7hb-n"/><path class="b5sph-bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-left-duotone-sharp" /></template>
<style>
.b5sph-bma {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 19h5l-7-7l7-7h-9l-7 7l7 7z");
}

.ft5dv1b6b {
  fill: none;
}

.u-y-7hb-n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 19h-9l-7-7l7-7h9l-7 7Z");
}

</style>
