<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iala1ccfk"/><path class="g3cyggwvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-batch-request" /></template>
<style>
.g3cyggwvm {
  d: path("m8 2.25l2.5 2.5L8 7.25");
}

.iala1ccfk {
  d: path("M10.5 2.5h11V7h-11Zm0 7.25h11v4.5h-11Zm0 7.25h11v4.5h-11Zm-8-12.25h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
