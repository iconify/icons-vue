<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ml0540bqo"/><path class="j_34204tq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-hall-clock" /></template>
<style>
.j_34204tq {
  d: path("M12 5.25V7l1.5 1M10 21v-2.75a2 2 0 0 1 4 0V21");
}

.ml0540bqo {
  d: path("M7.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM3 21v-7h5.5v-3m7 0v3H21v7M2.5 21h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
