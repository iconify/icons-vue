<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdwu4gb4m"/><path class="tsm53-xwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-sugar" /></template>
<style>
.jdwu4gb4m {
  d: path("M11.683 18.322a5.8 5.8 0 0 1-2.183.428c-3.25 0-6-2.75-6-6c0-3.5 3-6.5 6-10.25c2.89 3.612 5.779 6.528 5.988 9.866M18 14.25L21.5 16v4L18 21.75L14.5 20v-4Z");
}

.tsm53-xwj {
  d: path("m14.5 16l3.5 1.75L21.5 16M18 17.75v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
