<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="wczli4bgo"/><path class="p12kz2bkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-documents-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p12kz2bkg {
  d: path("M2 13L2 5L16 5");
}

.wczli4bgo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 8L22 8C22.5523 8 23 8.4477 23 9L23 16.536C23 17.0883 22.5523 17.536 22 17.536C21.8245 17.536 21.652 17.4898 21.5 17.402L20 16.5359C19.3919 16.1848 18.7022 16 18 16C16.741 16 15.5554 16.5928 14.8 17.6C13.6668 19.1108 11.8886 20 10 20C8.1114 20 6.3332 19.1108 5.2 17.6C5.0702 17.4269 5 17.2164 5 17L5 9C5 8.4477 5.4477 8 6 8Z");
  stroke: none;
}

</style>
