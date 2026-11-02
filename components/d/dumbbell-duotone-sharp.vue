<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j108vjbyb"/><path class="t_c5-vm7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j108vjbyb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 4a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-2H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h1V5a1 1 0 0 1 1-1Zm10 0a1 1 0 0 1 1 1v2h1a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-1v2a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Z");
}

.t_c5-vm7q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5h4v14H5Zm10 0h4v14h-4ZM5 8H3v8h2m14-8h2v8h-2M9 12h6");
}

</style>
