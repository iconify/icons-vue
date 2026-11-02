<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rslf4ob0g"/><path class="obk3f0huh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-alt-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.obk3f0huh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h18v14H3Zm8 10c-2 0-2-3 0-3m4 0c2 0 2 3 0 3s-2-3 0-3");
}

.rslf4ob0g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 5v14H3V5Z");
}

</style>
