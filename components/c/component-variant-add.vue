<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k09q2cc7h"/><path class="k87-d6w-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:component-variant-add" /></template>
<style>
.k09q2cc7h {
  d: path("M12.244 16.006L10.25 18L2.5 10.25l7.75-7.75L18 10.25l-1.937 1.937m-.849.849l-2.192 2.192");
}

.k87-d6w-v {
  d: path("m10.25 7.75l2.5 2.5l-2.5 2.5l-2.5-2.5ZM18 15v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
