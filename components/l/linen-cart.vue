<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qlpdpbccs"/><path class="wqwmc-dnb"/><path class="fb8cv3u9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:linen-cart" /></template>
<style>
.fb8cv3u9f {
  d: path("m20 6l1.5-2");
}

.qlpdpbccs {
  d: path("M4 6v13.5M20 6v13.5m-16-6h16m-16 6h16M6 10h12v3.5H6Zm1.5-3.5h9V10h-9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqwmc-dnb {
  fill: currentColor;
  d: path("M4.25 21.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm14 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

</style>
