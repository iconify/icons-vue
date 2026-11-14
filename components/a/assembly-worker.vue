<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuopwrbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:assembly-worker" /></template>
<style>
.yuopwrbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5h1.5a4 4 0 0 1 8 0H16Zm2 0v2a3.5 3.5 0 0 0 7 0v-2M3 21c0-3.5 3.5-6 7.5-6c1.415 0 2.768.313 3.926.873m5.708-1.775l1.768 1.768l-3.536 3.536l-1.768-1.768ZM17.5 18.5l-2.75 2.75");
}

</style>
