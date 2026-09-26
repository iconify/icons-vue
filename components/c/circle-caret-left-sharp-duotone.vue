<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ozqsggbsj"/><path class="nd1h41chj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-left-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nd1h41chj {
  d: path("M7 12L16 17L16 7L7 12Z");
}

.ozqsggbsj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C6.0629 1 1 6.0629 1 12C1 17.937 6.0629 23 12 23C17.937 23 23 17.937 23 12C23 6.0629 17.937 1 12 1Z");
  stroke: none;
}

</style>
