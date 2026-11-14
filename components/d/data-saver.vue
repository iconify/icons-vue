<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xl3y4sj2q"/><path class="j-kanxclm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-saver" /></template>
<style>
.j-kanxclm {
  d: path("M8.75 12.25L12 15.5l3.25-3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xl3y4sj2q {
  d: path("m12 2.5l7.5 3V11c0 5-3 8.5-7.5 10.5c-4.5-2-7.5-5.5-7.5-10.5V5.5Zm0 5v8");
}

</style>
