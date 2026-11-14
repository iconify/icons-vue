<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v9m7xnbcq"/><path class="do6653bbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:duplex" /></template>
<style>
.do6653bbn {
  d: path("M6 21.5v-4h3v4m6 0v-4h3v4m-10.75-9h.01m9.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9m7xnbcq {
  d: path("m2.5 11l4.75-6L12 11l4.75-6l4.75 6v10.5h-19Zm9.5 0v10.5");
}

</style>
