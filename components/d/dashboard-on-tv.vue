<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nwi5hpb8f"/><path class="os7dqtb4r"/><path class="uzektbbhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-on-tv" /></template>
<style>
.nwi5hpb8f {
  d: path("M2.5 3h19v13.5h-19ZM12 16.5V21m-4.5 0h9");
}

.os7dqtb4r {
  d: path("M5.5 6h5v7.5h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzektbbhu {
  fill: currentColor;
  d: path("M13.5 6h5v2.25h-5Zm0 5.25h5v2.25h-5Z");
}

</style>
