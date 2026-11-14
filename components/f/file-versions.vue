<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="vr2mifb3q"/><path class="yby7enb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-versions" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwivq1yig {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

.vr2mifb3q {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8.752 12.625a3.75 3.75 0 1 1 1.373 5.123");
}

.yby7enb4u {
  d: path("m10.75 11.75l-2 .75l-.25-2m3.5 2.25v1.75l1.25 1");
}

</style>
