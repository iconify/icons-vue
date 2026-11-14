<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ht-l2qb3f"/><path class="iloxv9qhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badge-ribbon" /></template>
<style>
.ht-l2qb3f {
  d: path("m12 2.25l1.488 1.196l1.887-.292l.691 1.78l1.78.691l-.292 1.887L18.75 9l-1.196 1.488l.292 1.887l-1.78.691l-.691 1.78l-1.887-.292L12 15.75l-1.488-1.196l-1.887.292l-.691-1.78l-1.78-.691l.292-1.887L5.25 9l1.196-1.488l-.292-1.887l1.78-.691l.691-1.78l1.887.292Z");
}

.iloxv9qhl {
  d: path("M8.75 14.5v7L12 19.25l3.25 2.25v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
