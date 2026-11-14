<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ce1tk347n"/><path class="l551_rgox"/><path class="miq9nebuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ballot-paper-pen" /></template>
<style>
.ce1tk347n {
  d: path("M12.3 19H3.5V2.5H18v8.9");
}

.l551_rgox {
  d: path("M7 6h5.5v5.5H7Z");
}

.miq9nebuq {
  d: path("m8.5 8.75l1.5 1.5l4.5-4.75M7 15h4m3.745 5.755l.707-2.828l4.243-4.243l2.121 2.121l-4.243 4.243Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
