<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eia6kcbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-unread" /></template>
<style>
.eia6kcbyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6a2.5 2.5 0 0 1 2.5-2.5h6.25A6 6 0 0 0 20 10.75V14a2.5 2.5 0 0 1-2.5 2.5H11L7 20v-3.5h-.5A2.5 2.5 0 0 1 4 14Zm12.25-1.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM8 10h5");
}

</style>
