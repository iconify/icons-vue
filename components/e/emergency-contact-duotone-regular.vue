<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-icpcn9a"/><path class="n-v7cf2vd"/><path class="u4ozpubdi"/><path class="eb5zxsbop"/><path class="mz4c5lb-h"/><path class="meft4rjfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:emergency-contact-duotone-regular" /></template>
<style>
.eb5zxsbop {
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
}

.meft4rjfc {
  d: path("M13.5 11a3.5 3.5 0 0 1 7 0");
}

.mz4c5lb-h {
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n-v7cf2vd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4ozpubdi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 11a3.5 3.5 0 0 1 7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w-icpcn9a {
  fill: currentColor;
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
