<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lzstiymuo"/><circle class="mqr0q0b_r"/><path class="l3vdmpblf"/><path class="tf01pxl-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-tunisia" /></template>
<style>
.l3vdmpblf {
  fill: var(--svg-color--e70013, #e70013);
  d: path("M15.4 18a3.9 3.9 0 0 1 6.541-2.869a4.875 4.875 0 1 0 0 5.738A3.9 3.9 0 0 1 15.4 18");
}

.lzstiymuo {
  fill: var(--svg-color--e70013, #e70013);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.mqr0q0b_r {
  cx: 18px;
  cy: 18px;
  r: 6.5px;
  fill: var(--svg-color--fff, #fff);
}

.tf01pxl-x {
  fill: var(--svg-color--e70013, #e70013);
  d: path("m19.645 16.937l-1.249-1.719v2.125L16.375 18l2.021.657v2.125l1.249-1.719l2.021.656L20.417 18l1.249-1.719z");
}

</style>
