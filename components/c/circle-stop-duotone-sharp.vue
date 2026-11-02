<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lfjlw55zm"/><path class="bdkc1jnbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-stop-duotone-sharp" /></template>
<style>
.bdkc1jnbf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m6-3h6v6H9Z");
}

.ft5dv1b6b {
  fill: none;
}

.lfjlw55zm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 21a9 9 0 0 1-9-9a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9m3-12H9v6h6Z");
}

</style>
