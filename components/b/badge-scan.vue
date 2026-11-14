<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r7cwdqbfh"/><path class="orvjxtbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-scan" /></template>
<style>
.orvjxtbkh {
  d: path("M10.25 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8.5 18.75c0-2 1.5-3.5 3.5-3.5s3.5 1.5 3.5 3.5m-13 0h19");
}

.r7cwdqbfh {
  d: path("M4.5 6h15v15.5h-15ZM10 6V2.5M14 6V2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
