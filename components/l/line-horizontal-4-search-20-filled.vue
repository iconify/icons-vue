<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yv2gr5b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-search-20-filled" /></template>
<style>
.yv2gr5b8s {
  fill: currentColor;
  d: path("M12.5 10a4.5 4.5 0 0 0 2.607-.832l3.613 3.612a.75.75 0 1 0 1.06-1.06l-3.612-3.613A4.5 4.5 0 1 0 12.5 10m0-7.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6m3.025 8.5l1.5 1.5H2.75a.75.75 0 0 1 0-1.5zM2.75 3H7.6a5.5 5.5 0 0 0-.51 1.5H2.75a.75.75 0 0 1 0-1.5m0 4h4.457c.152.538.384 1.043.682 1.5H2.75a.75.75 0 0 1 0-1.5M2 15.75a.75.75 0 0 1 .75-.75h14.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75");
}

</style>
