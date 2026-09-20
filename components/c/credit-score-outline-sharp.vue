<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqvk_g9kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-score-outline-sharp" /></template>
<style>
.wqvk_g9kf {
  fill: currentColor;
  d: path("M4 8h16V6H4zM2 20V4h20v8H4v6h4.1v2zm12.95 2l-4.25-4.25l1.4-1.4l2.85 2.8l5.65-5.65l1.4 1.45zM4 18v-4.5v2.825V6z");
}

</style>
