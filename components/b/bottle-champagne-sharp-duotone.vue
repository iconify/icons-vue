<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lkpzk7e2z"/><path class="mbano5vlp"/><path class="kj99aw-3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-champagne-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kj99aw-3j {
  fill: currentColor;
  d: path("M7 1L5 1C4.4477 1 4 1.4477 4 2L4 5C4 5.5523 4.4477 6 5 6L5.5 6L8.5 6L9 6C9.5523 6 10 5.5523 10 5L10 2C10 1.4477 9.5523 1 9 1ZM7 14L3 14C2.4477 14 2 14.4477 2 15L2 22C2 22.5523 2.4477 23 3 23L11 23C11.5523 23 12 22.5523 12 22L12 15C12 14.4477 11.5523 14 11 14ZM22 9L22 6C22 5.4477 21.5523 5 21 5L15 5C14.4477 5 14 5.4477 14 6L14 12C14 13.3894 14.5921 14.6105 15.3221 15.474C16.0056 16.2825 17.0094 17 18 17C18.9906 17 19.9944 16.2825 20.6779 15.474C21.4079 14.6105 22 13.3894 22 12Z");
  stroke: none;
}

.lkpzk7e2z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 23L11 23C11.5523 23 12 22.5523 12 22L12 15L12 12C12 10.3825 11.1704 9.2689 10.5426 8.4528C10.2086 8.0185 9.9517 7.6961 9.7609 7.359C9.583 7.0447 9.5 6.7774 9.5 6.5L9.5 5.8662C9.7989 5.6933 10 5.3701 10 5L10 2C10 1.4477 9.5523 1 9 1L5 1C4.4477 1 4 1.4477 4 2L4 5C4 5.3701 4.2011 5.6933 4.5 5.8662L4.5 6.5C4.5 6.7774 4.417 7.0447 4.2391 7.359C4.0483 7.6961 3.7914 8.0185 3.4574 8.4528C2.8296 9.2689 2 10.3825 2 12L2 15L2 22C2 22.5523 2.4477 23 3 23Z");
  stroke: none;
}

.mbano5vlp {
  stroke-opacity: 0.4;
  d: path("M18 16L18 22M14 22L15 22L18 22L22 22");
}

</style>
