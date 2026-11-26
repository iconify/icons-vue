<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eq2lywkqe"/><path class="ezm7kubbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-buffer-tri-state-two-tone" /></template>
<style>
.eq2lywkqe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.4712 9.7516L17.9712 12.2516C18.6062 12.6044 19 13.2736 19 14C19 14.7264 18.6062 15.3956 17.9713 15.7483L8.9712 20.7484C8.6741 20.9134 8.3397 21 8 21C6.8954 21 6 20.1046 6 19L6 9C6 7.8954 6.8954 7 8 7C8.3397 7 8.6741 7.0866 8.9712 7.2516Z");
  stroke: none;
}

.ezm7kubbs {
  d: path("M8.4856 8.1258L17.4856 13.1258C17.8031 13.3022 18 13.6368 18 14C18 14.3632 17.8031 14.6978 17.4856 14.8742L8.4856 19.8742C8.3371 19.9567 8.1699 20 8 20C7.4477 20 7 19.5523 7 19L7 9C7 8.4477 7.4477 8 8 8C8.1699 8 8.3371 8.0433 8.4856 8.1258ZM2 14L7 14M18 14L22 14M13 4L13 10.6338");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
