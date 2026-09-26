<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="v2ib7t5ke"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-off-fill" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v2ib7t5ke {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 18.75C16.8543 20.1721 14.5069 21 12 21C6.7383 21 2.1794 17.3529 1.0244 12.2195C0.9919 12.075 0.9919 11.925 1.0244 11.7805C1.6291 9.0929 3.1668 6.8127 5.25 5.25ZM9.1708 4.9282C8.9114 4.6688 8.8148 4.2882 8.9193 3.9365C9.0237 3.5848 9.3123 3.3185 9.6713 3.2427C10.4252 3.0834 11.2046 3 12 3C17.2617 3 21.8206 6.6471 22.9756 11.7805C23.0081 11.925 23.0081 12.075 22.9756 12.2195C22.6998 13.4454 22.2298 14.5865 21.6025 15.6135C21.4427 15.8751 21.1718 16.049 20.8674 16.0852C20.563 16.1215 20.2587 16.0161 20.042 15.7993L9.1708 4.9282ZM14.8284 14.8284C14.1046 15.5523 13.1046 16 12 16C9.7909 16 8 14.2091 8 12C8 10.8955 8.4477 9.8955 9.1716 9.1716ZM13.4142 13.4142C13.0523 13.7762 12.5523 14 12 14C10.8954 14 10 13.1046 10 12C10 11.4477 10.2238 10.9477 10.5858 10.5858Z");
  stroke: none;
}

</style>
