<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-kj5_bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:currency-lira-outline" /></template>
<style>
.o-kj5_bjy {
  fill: currentColor;
  d: path("M9.5 20v-5.054l-3 1.875V15.62l3-1.875v-3.523l-3 1.875V10.92l3-1.9V4h1v4.404l4-2.5V7.08l-4 2.525v3.523l4-2.5v1.177l-4 2.525V19h.5q2.075 0 3.672-1.386T16.462 14h1.019q-.173 2.56-2.028 4.28T11 20z");
}

</style>
