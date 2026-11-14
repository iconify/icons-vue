<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="weez58bvj"/><path class="byvt__2ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:destination-pin" /></template>
<style>
.byvt__2ql {
  d: path("m12 6.25l.882 2.036l2.209.21l-1.664 1.468l.483 2.165L12 11l-1.91 1.129l.483-2.165l-1.664-1.468l2.209-.21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.weez58bvj {
  d: path("M12 21.5S4.5 15 4.5 9.5a7.5 7.5 0 0 1 15 0c0 5.5-7.5 12-7.5 12Z");
}

</style>
