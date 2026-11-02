<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eocsbobaj"/><path class="l3a6zpdfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-duotone-sharp" /></template>
<style>
.eocsbobaj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 12c.265 0 .52.105.707.293L10.414 15h3.172l2.707-2.707A1 1 0 0 1 17 12h4a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.l3a6zpdfy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v16H3Zm0 9h4l3 3h4l3-3h4");
}

</style>
