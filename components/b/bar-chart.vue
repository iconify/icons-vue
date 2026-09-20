<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t8v0an0fk"/><path class="wwfuhccxz"/><path class="rymvb_4nn"/><path class="xzcgvsb2b"/><path class="eiyxqpb7x"/><path class="az8i8-63v"/><path class="ur0zjdbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:bar-chart" /></template>
<style>
.az8i8-63v {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M124 120H8V4H4v120h120z");
}

.eiyxqpb7x {
  fill: var(--svg-color--0091ea, #0091ea);
  d: path("M103.64 121.91H91.73c-1.36 0-2.46-1.1-2.46-2.46V25.86c0-1.36 1.1-2.46 2.46-2.46h11.91c1.36 0 2.46 1.1 2.46 2.46v93.59c0 1.36-1.1 2.46-2.46 2.46");
}

.rymvb_4nn {
  fill: var(--svg-color--9ccc65, #9ccc65);
  d: path("M38.72 121.91H21.89V55.38c0-1.36 1.1-2.46 2.46-2.46h11.91c1.36 0 2.46 1.1 2.46 2.46z");
}

.t8v0an0fk {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4h120v120H4z");
}

.ur0zjdbif {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M122 6v116H6V6zm2-2H4v120h120z");
}

.wwfuhccxz {
  fill: none;
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M124 24.35H5.57M124 43.67H5.47M124 62.99H5.36M124 82.31H5.26M124 101.64H5.15");
}

.xzcgvsb2b {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M72.42 121.91H55.58V74.84c0-1.36 1.1-2.46 2.46-2.46h11.91c1.36 0 2.46 1.1 2.46 2.46v47.07z");
}

</style>
