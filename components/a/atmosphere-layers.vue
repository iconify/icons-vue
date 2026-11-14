<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mm3ooywih"/><path class="hs2zz94xq"/><path class="hul4rvhlx"/><path class="opjk_568w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atmosphere-layers" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

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

</style>
