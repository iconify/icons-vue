<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bgo-1qxmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-arrow-back-48-regular" /></template>
<style>
.bgo-1qxmn {
  fill: currentColor;
  d: path("M35 24c6.075 0 11 4.925 11 11s-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11m2.75-18A4.25 4.25 0 0 1 42 10.25v3.5c0 1.52-.8 2.853-2 3.605v5.641a13 13 0 0 0-2.5-.756V18h-27v17.75a3.75 3.75 0 0 0 3.75 3.75h8.55c.326.882.744 1.72 1.244 2.5H14.25A6.25 6.25 0 0 1 8 35.75V17.355c-1.2-.752-2-2.084-2-3.605v-3.5A4.25 4.25 0 0 1 10.25 6zm-6.043 24.293a1 1 0 0 0-1.414 0l-3 3a1 1 0 0 0 0 1.414l3 3a1 1 0 1 0 1.414-1.414L30.414 35H36a4 4 0 0 1 4 4a1 1 0 1 0 2 0a6 6 0 0 0-6-6h-5.586l1.293-1.293a1 1 0 0 0 0-1.414M27.75 22a1.25 1.25 0 0 1 1.227 1.477q-.861.451-1.642 1.023H20.25a1.25 1.25 0 1 1 0-2.5zM10.25 8.5a1.75 1.75 0 0 0-1.75 1.75v3.5c0 .966.784 1.75 1.75 1.75h27.5a1.75 1.75 0 0 0 1.75-1.75v-3.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
