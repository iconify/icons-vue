<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="actrzi01v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-delete" /></template>
<style>
.actrzi01v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.772 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.385 0 .757.024M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m7.5 7.5h8m-5.25 0v-1.75h2.5v1.75m-2.593 0h2.686a1.5 1.5 0 0 1 1.492 1.649l-.45 4.5A1.5 1.5 0 0 1 18.893 22h-1.786a1.5 1.5 0 0 1-1.492-1.351l-.45-4.5a1.5 1.5 0 0 1 1.492-1.649m.593 2.5v2.5m1.5-2.5v2.5");
}

</style>
