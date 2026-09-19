<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv4_abj-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-density-small" /></template>
<style>
.bv4_abj-g {
  fill: currentColor;
  d: path("M3 2h18v2H3zm0 18h18v2H3zm0-6h18v2H3zm0-6h18v2H3z");
}

</style>
