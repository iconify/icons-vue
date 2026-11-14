<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qxak8bbmg"/><path class="yka-tbm_q"/><path class="jbuhziglf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hip" /></template>
<style>
.jbuhziglf {
  d: path("M10.75 10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L17.5 15v6.5m-6.25-9l2.75 3v6m3.5-6.5c1.5-.25 2.5-1 3-2m-18-3C3 13 5 15 8 15.75");
}

.qxak8bbmg {
  d: path("M2.5 10c0-4.5 3-7.5 7.5-7.5c2.75 0 4.5 1.25 4.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yka-tbm_q {
  d: path("M10.268 13.756a4.25 4.25 0 0 1 4.857-6.937");
}

</style>
