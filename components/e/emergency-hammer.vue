<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so9h1n5dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-hammer" /></template>
<style>
.so9h1n5dz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.795 4.487l1.037.183a1.5 1.5 0 0 1 .8.416l4.282 4.282a1.5 1.5 0 0 1 .416.8l.183 1.037a1.068 1.068 0 0 1-1.237 1.237l-1.037-.183a1.5 1.5 0 0 1-.8-.417l-4.281-4.281a1.5 1.5 0 0 1-.417-.8l-.183-1.037a1.068 1.068 0 0 1 1.237-1.237m1.503 5.215za1.5 1.5 0 0 1 0 2.121l-5.303 5.304a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l5.304-5.303a1.5 1.5 0 0 1 2.121 0M15.5 15l2.5 2.5l-1.5 1.75l3 2.5M18 17.5l3.75-1");
}

</style>
