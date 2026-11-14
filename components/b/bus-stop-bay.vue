<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s-b3xv35b"/><path class="rnnv5bx0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bus-stop-bay" /></template>
<style>
.rnnv5bx0i {
  d: path("M6.5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-11 2.5h2V21h15v-2.5h2");
}

.s-b3xv35b {
  d: path("M3 14V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v9Zm0-6h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
