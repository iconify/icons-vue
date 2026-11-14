<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3vr1b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hydroponic-jar" /></template>
<style>
.ru3vr1b_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9h9c1 1 1.5 2.5 1.5 4v6a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 6 19v-6c0-1.5.5-3 1.5-4ZM6 12.5h3.5m5 0H18M12 15V6m0 9l-2.5 3.5M12 15l2.5 3.5M12 6c0-2.25-1.75-3.5-4-3.5C8 4.75 9.75 6 12 6Zm0 0c0-2.25 1.75-3.5 4-3.5C16 4.75 14.25 6 12 6Z");
}

</style>
