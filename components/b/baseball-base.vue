<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dircedbbw"/><path class="ay2f4rb_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-base" /></template>
<style>
.ay2f4rb_p {
  d: path("M2.5 11v3l9.5 5l9.5-5v-3M12 16v3");
}

.dircedbbw {
  d: path("M2.5 11L12 6l9.5 5l-9.5 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
