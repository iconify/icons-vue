<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cml_e3ybx"/><path class="x4h68jbhs"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:case-pending" /></template>
<style>
.cml_e3ybx {
  d: path("M12.7 18.5H2.5V6H20v5.9M8 6V4.5A1.5 1.5 0 0 1 9.5 3H13a1.5 1.5 0 0 1 1.5 1.5V6m-12 5H20m-4.5 3.75h5m-5 6.5h5");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4h68jbhs {
  d: path("M16.5 14.75v1l3 4.5v1");
}

</style>
