<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mlzgjgbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-0-32-regular" /></template>
<style>
.mlzgjgbpe {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14s-6.268 14-14 14S2 23.732 2 16S8.268 2 16 2m0 2C9.373 4 4 9.373 4 16s5.373 12 12 12s12-5.373 12-12S22.627 4 16 4m-1.193 2.888c.343-1.178 2.043-1.178 2.386 0l.03.122c.544 2.765 1.107 5.529 1.564 8.31c.117.714.213 1.364.213 1.681a3 3 0 0 1-6 0c0-.317.096-.967.213-1.68c.374-2.28 1.164-6.3 1.563-8.311z");
}

</style>
