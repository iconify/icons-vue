<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vdnmfrbqo"/><path class="hwyp-cwtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:briefcase-open" /></template>
<style>
.hwyp-cwtv {
  d: path("M8.5 12V7.5h5l2 2V12M12 12v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vdnmfrbqo {
  d: path("M2.5 12h19v9.5h-19ZM5 12l.5-7.5h13L19 12");
}

</style>
