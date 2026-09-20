<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m_rpp-0xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-horizontal-descending-16-regular" /></template>
<style>
.m_rpp-0xb {
  fill: currentColor;
  d: path("M13 5a2 2 0 1 0 0-4H3a2 2 0 1 0 0 4zM2 3a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m5 12a2 2 0 1 0 0-4H3a2 2 0 1 0 0 4zm-5-2a1 1 0 0 1 1-1h4a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m9-5a2 2 0 0 1-2 2H3a2 2 0 1 1 0-4h6a2 2 0 0 1 2 2m-1 0a1 1 0 0 0-1-1H3a1 1 0 1 0 0 2h6a1 1 0 0 0 1-1");
}

</style>
