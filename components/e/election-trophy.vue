<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lwote8bwq"/><path class="uyh0bbb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:election-trophy" /></template>
<style>
.lwote8bwq {
  d: path("M6 3h12v5.5a6 6 0 0 1-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uyh0bbb6j {
  d: path("M6 5H3.5v1.5A3.5 3.5 0 0 0 6.25 10M18 5h2.5v1.5a3.5 3.5 0 0 1-2.75 3.5M12 14.5V18m-4 0h8v3H8Zm4-12.75l.882 1.786l1.971.287l-1.426 1.391l.336 1.963L12 9.75l-1.763.927l.336-1.963l-1.426-1.391l1.971-.287Z");
}

</style>
