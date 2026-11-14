<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cqqgs1b-q"/><path class="d5ygk9t5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:last-will-check" /></template>
<style>
.cqqgs1b-q {
  d: path("M13.8 21H3.5V2.5h14v12.8M7 7h7m-7 4h5");
}

.d5ygk9t5w {
  d: path("M7 16c1-2.5 2.5-2.5 3 0c.204 1.019.574 1.622 1.008 1.811M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
