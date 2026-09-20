<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-pndgz7k"/><path class="y_uork5-p"/><path class="me2guebva"/><path class="pkr04599e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:knowledge-cutoff-outline-thin" /></template>
<style>
.g-pndgz7k {
  d: path("M2 12h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.me2guebva {
  d: path("m18 9.5 3 3");
}

.pkr04599e {
  d: path("m21 9.5 -3 3");
}

.y_uork5-p {
  d: path("M15 7v10");
}

</style>
