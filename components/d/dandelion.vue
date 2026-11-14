<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hx28i2b-f"/><path class="ifxw_ccog"/><path class="qfnnvybzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dandelion" /></template>
<style>
.hx28i2b-f {
  d: path("M13.75 8.5H18m-7.75 0H6m6-1.75V2.5m1.25 4.75l3-3m-5.5 3l-3-3m5.5 5.5l3 3m-5.5-3l-3 3");
}

.ifxw_ccog {
  fill: currentColor;
  d: path("M12 8.5h.01");
}

.qfnnvybzf {
  d: path("M12 10.25V21.5m0 0c-2.5 0-5-1.5-5.5-4.5c3 .5 5 2 5.5 4.5Zm0 0c2.5 0 5-1.5 5.5-4.5c-3 .5-5 2-5.5 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
