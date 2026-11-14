<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iryne0nib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:confetti" /></template>
<style>
.iryne0nib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19.5Q6 15 9 17q2.5 1.5 3.5-1M6.451 3.585l2.598 1.5l-2.5 4.33l-2.598-1.5Zm8.149.612l4.532-2.113L20.4 4.803l-4.532 2.113Zm2.346 8.441l2.819 1.026l-1.711 4.698l-2.819-1.026ZM11.5 9.5h.01m8.49 11h.01");
}

</style>
