<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qakfjpo1e"/><path class="wphvxrb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-jewelry" /></template>
<style>
.qakfjpo1e {
  d: path("M8 4h8l4 5.5L12 21L4 9.5ZM4 9.5h16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wphvxrb5q {
  d: path("M12 21L9 9.5L11 4");
}

</style>
