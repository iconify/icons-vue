<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vop78xbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:anchor-simple-bold" /></template>
<style>
.vop78xbkx {
  fill: currentColor;
  d: path("M224 108h-24a12 12 0 0 0 0 24h11.15A84.21 84.21 0 0 1 140 203.14V97.94a36 36 0 1 0-24 0v105.2A84.21 84.21 0 0 1 44.85 132H56a12 12 0 0 0 0-24H32a12 12 0 0 0-12 12a108 108 0 0 0 216 0a12 12 0 0 0-12-12m-96-56a12 12 0 1 1-12 12a12 12 0 0 1 12-12");
}

</style>
