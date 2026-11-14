<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-jms0bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cage-fence" /></template>
<style>
.s-jms0bgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.121 3h5.758a1.5 1.5 0 0 1 1.06.439l4.622 4.622A1.5 1.5 0 0 1 21 9.121v5.758a1.5 1.5 0 0 1-.439 1.06l-4.622 4.622a1.5 1.5 0 0 1-1.06.439H9.121a1.5 1.5 0 0 1-1.06-.439l-4.622-4.622A1.5 1.5 0 0 1 3 14.879V9.121a1.5 1.5 0 0 1 .439-1.06l4.622-4.622A1.5 1.5 0 0 1 9.121 3M3.25 8.25l12.5 12.5m-7.5-17.5l12.5 12.5m-17.5 0l12.5-12.5m-7.5 17.5l12.5-12.5");
}

</style>
