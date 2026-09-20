<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bsc5k_ovj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-right-20-filled" /></template>
<style>
.bsc5k_ovj {
  fill: currentColor;
  d: path("M15.53 15.447a.75.75 0 0 0 .392-1.031l-2.5-5.001a.75.75 0 1 0-1.342.67l1.62 3.245l-9.817-4.32l10.663-4.57a.75.75 0 1 0-.59-1.378L2.762 7.857c-1.004.431-1.011 1.853-.01 2.293l10.466 4.606l-3.247 1.298a.75.75 0 1 0 .557 1.392z");
}

</style>
