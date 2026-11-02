<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h0xfmyznw"/><path class="epq_l2b-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-duotone-sharp" /></template>
<style>
.epq_l2b-t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m6 5l1-2h10l2 4H5zm0 2l1 12c.1 1.2.8 2 2 2h6c1.2 0 1.9-.8 2-2l1-12M7 12h10M7 16h10");
}

.ft5dv1b6b {
  fill: none;
}

.h0xfmyznw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.106 2.553A1 1 0 0 1 7 2h10c.379 0 .725.214.894.553l2 4A1 1 0 0 1 19 8H5a1 1 0 0 1-.894-1.447ZM17 11a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

</style>
