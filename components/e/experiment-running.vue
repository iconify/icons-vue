<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bp4vnyd7i"/><path class="nt_ifibzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:experiment-running" /></template>
<style>
.bp4vnyd7i {
  d: path("M10.453 19.5H2.5L8 9V2.5h4.5V9l2.32 4.429M6.25 12.5h8m1 5.5a2.75 2.75 0 0 1 5.5 0m-1.25-1l1.25 1.25l1-1.25");
}

.nt_ifibzk {
  d: path("M20.75 18a2.75 2.75 0 0 1-5.5 0m-1 1l1-1.25L16.5 19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
