<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7dbyrb5g"/><path class="s1sn-g6ve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gov-portal-user" /></template>
<style>
.k7dbyrb5g {
  d: path("M4 21.5V10a8 8 0 0 1 16 0v11.5");
}

.s1sn-g6ve {
  d: path("M9.25 10.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM7 21.5c0-4 2-5.5 5-5.5s5 1.5 5 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
