<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tn3srqg0o"/><path class="wphvxrb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-jewelry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tn3srqg0o {
  d: path("M8.764 4h6.472a1.5 1.5 0 0 1 1.213.618l2.923 4.019a1.5 1.5 0 0 1 .019 1.739l-6.16 8.854a1.5 1.5 0 0 1-2.462 0l-6.16-8.854a1.5 1.5 0 0 1 .019-1.739l2.923-4.019A1.5 1.5 0 0 1 8.764 4M4 9.5h16");
}

.wphvxrb5q {
  d: path("M12 21L9 9.5L11 4");
}

</style>
