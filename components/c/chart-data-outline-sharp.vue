<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="necjmr63b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chart-data-outline-sharp" /></template>
<style>
.necjmr63b {
  fill: currentColor;
  d: path("m7.4 16l3.05-3.05l2 2L16 11.425V13h2V8h-5v2h1.575l-2.125 2.125l-2-2L6 14.6zM3 21V3h18v18zm2-2h14V5H5zM5 5v14z");
}

</style>
