<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ern327bwf"/><path class="lvihc9bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:appointment-office" /></template>
<style>
.ern327bwf {
  d: path("M11.7 19.5H2.5v-15h16v7.2M7 2.5v4m7-4v4");
}

.lvihc9bzf {
  d: path("M6 9.5h4v4H6Zm8.5 7H22V22h-7.5Zm2 0v-1a1 1 0 0 1 1-1H19a1 1 0 0 1 1 1v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
