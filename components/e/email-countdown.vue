<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bic4-_k3z"/><path class="qov011jqm"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-countdown" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.bic4-_k3z {
  d: path("M12.1 19.5H2.5v-15h19v8.6");
}

.qov011jqm {
  d: path("m2.5 7.5l9.5 6l9.5-6M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
