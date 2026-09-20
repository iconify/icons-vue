<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="glhd4acgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chalkboard-fill" /></template>
<style>
.glhd4acgb {
  fill: currentColor;
  d: path("M240 192h-8V56a16 16 0 0 0-16-16H40a16 16 0 0 0-16 16v136h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16m-24 0h-72v-16a8 8 0 0 1 8-8h56a8 8 0 0 1 8 8Zm0-48a8 8 0 0 1-16 0V72H56v112a8 8 0 0 1-16 0V64a8 8 0 0 1 8-8h160a8 8 0 0 1 8 8Z");
}

</style>
