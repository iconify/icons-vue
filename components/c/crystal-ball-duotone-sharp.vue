<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rix44bbjm"/><path class="ta5pgbb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rix44bbjm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 17C1.266 12.293 4.581 3.009 12 3c7.419.009 10.734 9.293 5 14h2v4H5v-4Z");
}

.ta5pgbb0c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17C1.262 12.302 4.584 3 12 3s10.738 9.302 5 14M5 17h14v4H5Zm4-7a3 3 0 0 1 3-3");
}

</style>
