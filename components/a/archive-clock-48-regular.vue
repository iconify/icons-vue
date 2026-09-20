<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nprksbcrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-clock-48-regular" /></template>
<style>
.nprksbcrh {
  fill: currentColor;
  d: path("M35 24c6.075 0 11 4.925 11 11s-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11m2.75-18A4.25 4.25 0 0 1 42 10.25v3.5c0 1.52-.8 2.853-2 3.605v5.641a13 13 0 0 0-2.5-.756V18h-27v17.75a3.75 3.75 0 0 0 3.75 3.75h8.55c.326.882.744 1.72 1.244 2.5H14.25A6.25 6.25 0 0 1 8 35.75V17.355c-1.2-.752-2-2.084-2-3.605v-3.5A4.25 4.25 0 0 1 10.25 6zM35 27a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h5a1 1 0 1 0 0-2h-4v-6a1 1 0 0 0-1-1m-7.25-5a1.25 1.25 0 0 1 1.227 1.477q-.861.451-1.642 1.023H20.25a1.25 1.25 0 1 1 0-2.5zM10.25 8.5a1.75 1.75 0 0 0-1.75 1.75v3.5c0 .966.784 1.75 1.75 1.75h27.5a1.75 1.75 0 0 0 1.75-1.75v-3.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
