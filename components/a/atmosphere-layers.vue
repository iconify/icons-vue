<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mm3ooywih"/><path class="hs2zz94xq"/><path class="hul4rvhlx"/><path class="opjk_568w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atmosphere-layers" /></template>
<style>
.hs2zz94xq {
  d: path("M3 16a12 12 0 0 1 18 0");
}

.hul4rvhlx {
  d: path("M3 12.5a12 12 0 0 1 18 0");
}

.mm3ooywih {
  d: path("M3 19.5a12 12 0 0 1 18 0Z");
}

.opjk_568w {
  d: path("M3 9a12 12 0 0 1 18 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
