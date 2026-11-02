<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hptfdykna"/><path class="f4132kgkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-duotone" /></template>
<style>
.f4132kgkr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20v-8c0-.64.36-1.36 1-2l5-5a1.414 1.414 0 0 1 2 0l5 5c.64.64 1 1.36 1 2v8m-9 0v-4a2 2 0 1 1 4 0v4");
}

.ft5dv1b6b {
  fill: none;
}

.hptfdykna {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 20v-8c0-1.039.578-1.992 1.293-2.707l5-5a2.414 2.414 0 0 1 3.414 0l5 5C19.422 10.008 20 10.961 20 12v8a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1m10-4a2 2 0 1 0-4 0v4h4Z");
}

</style>
