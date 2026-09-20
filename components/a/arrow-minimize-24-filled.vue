<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcp-ztbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-minimize-24-filled" /></template>
<style>
.bcp-ztbod {
  fill: currentColor;
  d: path("M10.498 12.505a1 1 0 0 1 .993.884l.007.116v7.504a1 1 0 0 1-1.994.117l-.006-.117v-5.093l-5.791 5.792a1 1 0 0 1-1.32.083l-.095-.083a1 1 0 0 1-.083-1.32l.083-.095l5.788-5.788H2.996a1 1 0 0 1-.117-1.993l.117-.007zm3-10.505a1 1 0 0 1 .994.883l.007.117v5.087l5.793-5.794a1 1 0 0 1 1.32-.083l.095.083a1 1 0 0 1 .083 1.32l-.083.095l-5.797 5.795H21a1 1 0 0 1 .117 1.994l-.117.007h-7.5a1 1 0 0 1-.994-.883l-.006-.117V3a1 1 0 0 1 1-1");
}

</style>
