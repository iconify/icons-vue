<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yyqryjbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:building-office-fill" /></template>
<style>
.yyqryjbhm {
  fill: currentColor;
  d: path("M248 208h-16V96a8 8 0 0 0 0-16h-48V48a8 8 0 0 0 0-16H40a8 8 0 0 0 0 16v160H24a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16M80 72h16a8 8 0 0 1 0 16H80a8 8 0 0 1 0-16m-8 48a8 8 0 0 1 8-8h16a8 8 0 0 1 0 16H80a8 8 0 0 1-8-8m64 88H88v-48h48Zm8-80h-16a8 8 0 0 1 0-16h16a8 8 0 0 1 0 16m0-40h-16a8 8 0 0 1 0-16h16a8 8 0 0 1 0 16m72 120h-32V96h32Z");
}

</style>
