<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rhk03ob7e"/><path class="if-qhtb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloon-star" /></template>
<style>
.if-qhtb4f {
  d: path("M12 13.5c0 3 1.5 4.5.5 8");
}

.rhk03ob7e {
  d: path("m12 3l2.057 4.168l4.6.669l-3.328 3.245l.785 4.581L12 13.5l-4.114 2.163l.785-4.581l-3.328-3.245l4.6-.669Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
