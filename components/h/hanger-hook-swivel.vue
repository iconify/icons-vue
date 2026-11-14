<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="myzh2wb8t"/><path class="ww8s3yb2f"/><path class="ovafeep8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hanger-hook-swivel" /></template>
<style>
.myzh2wb8t {
  d: path("M12 15.5V9a3 3 0 1 0-3-3M2.5 21l9.5-5.5l9.5 5.5h-19");
}

.ovafeep8l {
  d: path("m14 11l1.5 1.5l-1.75 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ww8s3yb2f {
  d: path("M8.5 12.5a3.5 1.25 0 0 0 7 0");
}

</style>
