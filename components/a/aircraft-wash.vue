<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paesxbchc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-wash" /></template>
<style>
.paesxbchc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5v-7H4L7.5 16h12a1.75 1.75 0 0 1 0 3.5Zm8 0l2 2M6 3l1.25 3a1.5 1.5 0 1 1-2.5 0Zm6 0l1.25 3a1.5 1.5 0 1 1-2.5 0Zm6 0l1.25 3a1.5 1.5 0 1 1-2.5 0Z");
}

</style>
