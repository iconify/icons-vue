<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r5ckv5b1f"/><path class="s_e4mwxsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5ckv5b1f {
  stroke-opacity: 0.4;
  d: path("M10 7V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3M8 21v-4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4");
}

.s_e4mwxsj {
  d: path("M12 7h4a4 4 0 0 1 4 4v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-8a4 4 0 0 1 4-4zm-4 4h8");
}

</style>
