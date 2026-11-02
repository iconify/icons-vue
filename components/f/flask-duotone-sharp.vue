<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jjnbddbwa"/><path class="jr02fp_yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jjnbddbwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 14c.379 0 .725.214.894.553l3 6A1 1 0 0 1 20 22H4a1 1 0 0 1-.894-1.447l3-6A1 1 0 0 1 7 14Z");
}

.jr02fp_yr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3v6L4 21h16L14 9V3M8 3h8M7 15h10");
}

</style>
