<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hy4bl51dr"/><path class="zpkmj173e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-left-two-tone" /></template>
<style>
.hy4bl51dr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.6962 4.0134C17.8249 4.0327 17.9499 4.0681 18.0683 4.1189C18.601 4.3474 18.9997 4.8758 18.9999 5.528L18.9999 18.4714C18.9998 18.8339 18.8766 19.1581 18.6757 19.4138C18.5956 19.5158 18.5033 19.607 18.4013 19.6853C17.9412 20.0385 17.2881 20.1311 16.707 19.7878L5.7499 13.3171C4.7499 12.7264 4.7499 11.2731 5.7499 10.6823L16.707 4.2116C17.0297 4.021 17.3745 3.9652 17.6962 4.0134Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zpkmj173e {
  d: path("M6.25868 12.456L17.2159 18.9273C17.5635 19.1326 18 18.8787 18 18.4713V5.52868C18 5.12126 17.5635 4.86742 17.2159 5.0727L6.25868 11.544C5.91377 11.7477 5.91377 12.2523 6.25868 12.456Z");
}

</style>
