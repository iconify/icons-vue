<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ckjkddbah"/><path class="ffhmct_qe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:image-off" /></template>
<style>
.ckjkddbah {
  d: path("M7.9 4H21v13.1M16.1 20H3V6.9m0 9.6l4.738-4.738");
}

.ffhmct_qe {
  d: path("M14 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM3.5 3.5l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
