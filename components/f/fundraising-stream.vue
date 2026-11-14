<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jqzcz_4uu"/><path class="gd-kh-v8m"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fundraising-stream" /></template>
<style>
.gd-kh-v8m {
  d: path("m9.5 6.5l6 3.25l-6 3.25ZM14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.jqzcz_4uu {
  d: path("M11.4 16.5H2.5V3h19v9.8M10 16.5v4m-3.5 0h5.3");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
