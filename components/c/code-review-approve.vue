<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z1_fg_b8e"/><path class="om35p7bhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-review-approve" /></template>
<style>
.om35p7bhc {
  d: path("m8 7.5l-2 3l2 3m3-6l2 3l-2 3m3.75 4.5l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1_fg_b8e {
  d: path("M11.8 19H3V2.5h13v12.8");
}

</style>
