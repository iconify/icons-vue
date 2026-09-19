<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k5vjq6-fq"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:k-shop" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.k5vjq6-fq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.557 25.992l8.665 11.28h-3.21c-1.33 0-2.015-.872-2.72-1.798l-5.036-6.616l5.038-6.332c.704-.925 1.39-1.798 2.72-1.798h3.209l-6.325 8.31zm-8.105-5.099h3.988v16.17h-3.988zm26.543-3.782a3.2 3.2 0 0 1-1.185.224c-1.853 0-3.345-1.561-3.345-3.5M37.454 5.5v8.335c0 1.939-1.492 3.5-3.345 3.5s-3.345-1.561-3.349-3.5c-.003 1.939-1.495 3.5-3.348 3.5s-3.345-1.561-3.345-3.5m-.001-7.834l-.005 7.834c-.006 1.939-1.498 3.5-3.35 3.5s-3.346-1.561-3.344-3.5c0 1.939-1.491 3.5-3.344 3.5s-3.345-1.561-3.351-3.5c-.006 1.939-1.498 3.5-3.35 3.5c-.47 0-.916-.1-1.321-.282M30.756 6.001v7.834m-13.39-7.834v7.834m-6.7-8.335v8.335");
}

</style>
