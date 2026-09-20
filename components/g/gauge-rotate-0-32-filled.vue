<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d8swetb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-0-32-filled" /></template>
<style>
.d8swetb_n {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14s-6.268 14-14 14S2 23.732 2 16S8.268 2 16 2m0 2.5C9.649 4.5 4.5 9.649 4.5 16S9.649 27.5 16 27.5S27.5 22.351 27.5 16S22.351 4.5 16 4.5m-1.193 2.388c.343-1.178 2.043-1.178 2.386 0l.03.122c.544 2.765 1.107 5.529 1.564 8.31c.117.714.213 1.364.213 1.681a3 3 0 0 1-6 0c0-.317.096-.967.213-1.68c.374-2.28 1.164-6.3 1.563-8.311z");
}

</style>
