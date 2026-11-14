<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q1k37nb3t"/><path class="hflyywb_z"/><path class="hudqbk_1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audit-queue" /></template>
<style>
.hflyywb_z {
  d: path("M5.25 8.5v-.75a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v11H13.5");
}

.hudqbk_1g {
  d: path("M8 5.75V5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v11h-2.75M5.5 15h5m-2-2.25L10.75 15L8.5 17.25");
}

.q1k37nb3t {
  d: path("M2.5 8.5h11v13h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
