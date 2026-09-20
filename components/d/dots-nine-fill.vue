<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hmmvy0odq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dots-nine-fill" /></template>
<style>
.hmmvy0odq {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M76 192a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-52a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-52a12 12 0 1 1 12-12a12 12 0 0 1-12 12m52 104a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-52a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-52a12 12 0 1 1 12-12a12 12 0 0 1-12 12m52 104a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-52a12 12 0 1 1 12-12a12 12 0 0 1-12 12m0-52a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
