<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8vzhqb-a"/><path class="xinpd7bpk"/><path class="sxbsk4rmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-copy" /></template>
<style>
.c8vzhqb-a {
  d: path("M2.5 13V4.5a2 2 0 0 1 2-2H13");
}

.sxbsk4rmu {
  d: path("m12 11l-2.5 3l2.5 3m4-6l2.5 3l-2.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xinpd7bpk {
  d: path("M6.5 6.5h15v15h-15Z");
}

</style>
