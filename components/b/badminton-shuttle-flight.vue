<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u_be9ybtg"/><path class="zz-nqqb-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badminton-shuttle-flight" /></template>
<style>
.u_be9ybtg {
  d: path("M15.5 6L18 8.5L14.5 15L9 9.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zz-nqqb-b {
  d: path("M16 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 17l3.5-3.5M7 21l3.5-3.5");
}

</style>
