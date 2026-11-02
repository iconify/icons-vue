<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gqimwbbba"/><path class="gji6bkbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-instance-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gji6bkbnt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 7l5 5l-10 10L2 12L12 2z");
}

.gqimwbbba {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 7l5 5l-10 10L2 12L12 2Z");
}

</style>
