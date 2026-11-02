<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="in9i2xbzf"/><path class="u68zyeb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.in9i2xbzf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 6a5 5 0 0 1 5 5v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-8a5 5 0 0 1 5-5Z");
}

.u68zyeb_k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7h4a4 4 0 0 1 4 4v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-8a4 4 0 0 1 4-4zm-4 4h8m-6-4V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3M8 21v-4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4");
}

</style>
