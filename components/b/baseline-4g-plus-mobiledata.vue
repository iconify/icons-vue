<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns3zh8b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-4g-plus-mobiledata" /></template>
<style>
.ns3zh8b5r {
  fill: currentColor;
  d: path("M13 11v2h2v2h-4V9h6c0-1.1-.9-2-2-2h-4c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h4c1.1 0 2-.9 2-2v-4zm11 0h-2V9h-2v2h-2v2h2v2h2v-2h2zM7 7H5v5H3V7H1v7h4v3h2v-3h1v-2H7z");
}

</style>
