<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eeody0b2d"/><path class="z1ggs_z8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-duotone" /></template>
<style>
.eeody0b2d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 20v-6.039c0-.607.276-1.182.751-1.561l3-2.4a2 2 0 0 1 2.498 0l3 2.4c.475.379.751.954.751 1.561V20Z");
}

.ft5dv1b6b {
  fill: none;
}

.z1ggs_z8f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M9 20v-6.039a2 2 0 0 1 .75-1.561l3-2.4a2 2 0 0 1 2.5 0l3 2.4a2 2 0 0 1 .75 1.56V20m-7-9.4V4H7a2 2 0 0 0-2 2v14");
}

</style>
