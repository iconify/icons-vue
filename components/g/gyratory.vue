<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vz1dcfb4q"/><path class="gwvx2rbui"/><path class="tfo2qlbsq"/><path class="r2z4h93uc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gyratory" /></template>
<style>
.gwvx2rbui {
  d: path("m18 10l2 2l2-2m-3.75 7.25A8 8 0 0 1 8 19");
}

.r2z4h93uc {
  d: path("M5.25 4.25L8 5l-.75 2.75M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.tfo2qlbsq {
  d: path("M10.75 18.25L8 19l.75 2.75m-4.25-7A8 8 0 0 1 8 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vz1dcfb4q {
  d: path("M13.5 4.25A8 8 0 0 1 20 12");
}

</style>
