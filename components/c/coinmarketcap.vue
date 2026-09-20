<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pw2vsltuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coinmarketcap" /></template>
<style>
.pw2vsltuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.935 39.466A21.499 21.499 0 1 1 45.5 24c-.182 8.576-9.348 10.014-10.25 1.656l-1.342-8.85l-11.192 14.817l-1.342-15.96l-14.96 20.7");
}

</style>
