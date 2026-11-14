<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="he4hywb2n"/><path class="b_msbgbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chequered-flags-crossed" /></template>
<style>
.b_msbgbdh {
  fill: currentColor;
  d: path("m2.5 5.25l2.75-.75L6 7l-2.5.75ZM6 7l2.75-1l1 2.75L7 9.5Zm15.5-1.75l-2.75-.75L18 7l2.5.75ZM18 7l-2.75-1l-1 2.75L17 9.5Z");
}

.he4hywb2n {
  d: path("m14 21.5l-6-18m2 18l6-18m-8 0l1.75 5.25l-5.5 1.75L2.5 5.25Zm8 0l-1.75 5.25l5.5 1.75l1.75-5.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
