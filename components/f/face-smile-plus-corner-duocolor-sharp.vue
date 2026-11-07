<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zru_ykc-c"/><path class="th3mjgbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-smile-plus-corner-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.th3mjgbmc {
  d: path("M14.049 3.236C8.403 1.916 3 6.202 3 12a9 9 0 0 0 9 9c5.798 0 10.084-5.403 8.764-11.049M9 9h.01M15 9h.01M8 14a5.657 5.657 0 0 0 8 0");
}

.zru_ykc-c {
  stroke-opacity: 0.4;
  d: path("M18 4h4m-2-2v4");
}

</style>
