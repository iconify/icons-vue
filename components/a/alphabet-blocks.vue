<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ez9ocwb-e"/><path class="r9dmfcbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alphabet-blocks" /></template>
<style>
.ez9ocwb-e {
  d: path("M3 12h8.5v8.5H3Zm9.5 0H21v8.5h-8.5ZM7.75 3h8.5v8.5h-8.5Z");
}

.r9dmfcbxm {
  d: path("m5.5 18l1.75-3.25L9 18m6.5-3.5V18M12 5.5h2L12 8h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
