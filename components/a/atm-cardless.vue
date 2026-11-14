<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n07itxu7p"/><path class="s6ae1gbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-cardless" /></template>
<style>
.n07itxu7p {
  d: path("M12.4 21.5H4v-19h16v8.7");
}

.s6ae1gbwr {
  d: path("M7 5h10v6H7Zm-.5 8.75h5.9m-5.65 3.5h.01m2.49 0h.01m2.49 0h.01M15.25 14h5.5v7.75h-5.5ZM18 18.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
