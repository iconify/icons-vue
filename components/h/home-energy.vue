<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmptz25oz"/><path class="i1p58y1sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-energy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1p58y1sg {
  d: path("M11.676 10.432L9.9 12.8a.75.75 0 0 0 .6 1.2a1.23 1.23 0 0 1 1.206 1.471l-.081.404a.41.41 0 0 0 .736.319l1.767-2.473A.772.772 0 0 0 13.5 12.5a1.213 1.213 0 0 1-1.186-1.467l.061-.283a.393.393 0 0 0-.699-.318");
}

.qmptz25oz {
  d: path("m4.422 9.714l5.875-5.011a2.625 2.625 0 0 1 3.406 0l5.875 5.011a2.63 2.63 0 0 1 .922 1.997v6.164a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875v-6.164a2.63 2.63 0 0 1 .922-1.997");
}

</style>
