<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lvrm-qbzq"/><path class="krfag1sus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-import" /></template>
<style>
.krfag1sus {
  d: path("M15.5 19.5v-4h4");
}

.lvrm-qbzq {
  d: path("M12.7 20.5H3.5V5h17v7.7M8 3v4m8-4v4M3.5 10h17M8 3v4m8-4v4M3.5 10h17m0 10.5l-5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
