<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_k_h0jif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antibiotic" /></template>
<style>
.t_k_h0jif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.096 3.075l2.829 2.829a1 1 0 0 1 0 1.414L7.318 17.925a1 1 0 0 1-1.414 0l-2.829-2.829a1 1 0 0 1 0-1.414L13.682 3.075a1 1 0 0 1 1.414 0ZM8.379 8.379l4.242 4.242M16 18.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm2.25-3.75V16m0 4.5V22m-3.75-3.75H16m4.5 0H22");
}

</style>
