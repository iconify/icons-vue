<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ogih1_44g"/><path class="ud-jh3bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-score" /></template>
<style>
.ogih1_44g {
  d: path("M12 3a9 9 0 1 1-9 9");
}

.ud-jh3bav {
  d: path("M12 15.5S8.25 13.25 8.25 11c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2c0 2.25-3.75 4.5-3.75 4.5ZM3 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
