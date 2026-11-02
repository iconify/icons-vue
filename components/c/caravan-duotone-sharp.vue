<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c9aoypmtg"/><path class="n0u1uccdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-duotone-sharp" /></template>
<style>
.c9aoypmtg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 5a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-4.171a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1Zm7.293 13.707l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

.ft5dv1b6b {
  fill: none;
}

.n0u1uccdw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 18H3V5h14v13h-5M7 9h6v4H7Zm1 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9-3h4");
}

</style>
