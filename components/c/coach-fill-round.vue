<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zadjokjnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coach-fill-round" /></template>
<style>
.zadjokjnr {
  fill: currentColor;
  d: path("M16 4a6 6 0 0 1 6 6v6c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16V9a5 5 0 0 1 5-5ZM8 6H7a3 3 0 0 0-3 3h4Zm2 0v3h3.78l-.6-3Zm10 4a3.98 3.98 0 0 0-1.15-2.807l-.002-.001l-.041-.041V7.15A3.98 3.98 0 0 0 16 6h-.78L16 9.901V11h4ZM6.291 18.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
