<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x-zcb8b1q"/><path class="zpbxqj6-m"/><path class="cvrj58bhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forwarded-many" /></template>
<style>
.cvrj58bhc {
  d: path("M9 18v-5.75A1.25 1.25 0 0 1 10.25 11h8.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-zcb8b1q {
  d: path("M3 12.5C3 7.5 6 5 11 5h6.5");
}

.zpbxqj6-m {
  d: path("M14.75 2.25L17.5 5l-2.75 2.75M12 14h9.5v7H12Z");
}

</style>
