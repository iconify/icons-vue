<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="civm8pnjw"/><path class="qcqkijbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:console-error" /></template>
<style>
.civm8pnjw {
  d: path("M14.6 18.5H2.5V3h19v8.6");
}

.qcqkijbqm {
  d: path("m6.5 7l3 3l-3 3m4.5 0h2.5m2 2.5l6 6m0-6l-6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
