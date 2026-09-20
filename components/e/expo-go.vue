<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvts3424h"/><circle class="zlo45vqyq"/><path class="tk1ab5uhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:expo-go" /></template>
<style>
.dvts3424h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.388 5.5l2.296 1.342l-9.28 5.358l-2.296-1.342zm-6.984 6.7L30.55 42.5l-3.715-2.183l-8.54-20.386l-7.982 10.732l-2.142-1.252l9.937-18.552M30.55 42.5l9.28-5.357l-3.395-10.14q-.32.056-.645.073a5.5 5.5 0 0 1-5.5-5.5a5.5 5.5 0 0 1 2.746-4.725l-3.351-10.01M20.36 24.862l-10.047 5.8");
}

.tk1ab5uhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.706 19.64za4 4 0 0 1-6.092 3.41");
}

.zlo45vqyq {
  cx: 35.79px;
  cy: 21.576px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
