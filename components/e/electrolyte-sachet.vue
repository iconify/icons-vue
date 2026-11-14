<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q9_hvmfnd"/><path class="a-cgikbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electrolyte-sachet" /></template>
<style>
.a-cgikbkh {
  d: path("m11.641 9.555l-1.812 2.317a.853.853 0 0 0 .671 1.378a1.32 1.32 0 0 1 1.269 1.683l-.269.942a.504.504 0 0 0 .888.441L14.2 13.9a.875.875 0 0 0-.7-1.4a1.302 1.302 0 0 1-1.247-1.676L12.5 10a.492.492 0 0 0-.859-.445");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9_hvmfnd {
  d: path("M5 4.5L7 3l2 1.5L11 3l2 1.5L15 3l2 1.5L19 3v18.5H5Z");
}

</style>
