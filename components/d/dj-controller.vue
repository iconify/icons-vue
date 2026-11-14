<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="de65v7bqf"/><path class="pptiyibfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dj-controller" /></template>
<style>
.de65v7bqf {
  d: path("M2 6.5h20v11H2Z");
}

.pptiyibfo {
  d: path("M4.75 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm9 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM7.5 12h.01m8.99 0h.01M12 9.25v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
