<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9jc5lbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ghostwriter" /></template>
<style>
.i9jc5lbpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5v-8a6 6 0 0 1 12 0v8l-2-1.5l-2 1.5l-2-1.5l-2 1.5l-2-1.5Zm4-7.5h.01m3.99 0h.01m5.865 11.125l.27-.991a1.5 1.5 0 0 1 .387-.666l2.093-2.093a1.237 1.237 0 0 1 1.75 0a1.29 1.29 0 0 1 .036 1.784l-1.914 2.073a1.5 1.5 0 0 1-.589.393l-1.069.388a.738.738 0 0 1-.964-.888");
}

</style>
