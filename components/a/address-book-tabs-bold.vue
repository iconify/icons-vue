<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="icelm3bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:address-book-tabs-bold" /></template>
<style>
.icelm3bnk {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-20 80h16v40h-16Zm16-24h-16V52h16ZM52 52h112v152H52Zm136 152v-32h16v32Zm-36.38-39a43.22 43.22 0 0 0-15.16-23a36 36 0 1 0-56.92 0a43.35 43.35 0 0 0-15.16 23a12 12 0 1 0 23.24 6c2.2-8.54 11-15 20.38-15s18.19 6.44 20.38 15a12 12 0 0 0 23.24-6M96 120a12 12 0 1 1 12 12a12 12 0 0 1-12-12");
}

</style>
