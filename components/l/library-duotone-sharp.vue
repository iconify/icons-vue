<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gh3kuxgrn"/><path class="q-f3-ovlb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:library-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gh3kuxgrn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 2a1 1 0 0 1 1 1v.719l2.757-.689a1 1 0 0 1 1.213.727l4 16a1 1 0 0 1-.727 1.213l-4 1a1 1 0 0 1-1.213-.727L13 13.123V21a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

.q-f3-ovlb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h8v18H4Zm4 0v18m8-17l4 16l-4 1l-4-16m0 0l4-1");
}

</style>
