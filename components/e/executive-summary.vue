<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xdm2q0b5x"/><path class="de6-s4bos"/><path class="jpoodhoru"/><path class="dy2rye3ut"/><path class="cmqdizble"/><path class="jvfqfih9p"/><path class="tukdhobyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:executive-summary" /></template>
<style>
.cmqdizble {
  d: path("M10.5 11.5h3.4");
}

.de6-s4bos {
  fill: currentColor;
  d: path("M7 7a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.dy2rye3ut {
  fill: currentColor;
  d: path("M7 11.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.jpoodhoru {
  d: path("M10.5 7h5");
}

.jvfqfih9p {
  fill: currentColor;
  d: path("M7 16a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.tukdhobyb {
  d: path("M10.5 16H13m3.75-1.75h2.5L18.5 16h-1l-.75-1.75M17.5 16l-1.75 4L18 21.75L20.25 20l-1.75-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdm2q0b5x {
  d: path("M13.1 21.5H4v-19h15v8.9");
}

</style>
