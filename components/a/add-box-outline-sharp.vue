<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3yrx0tkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-box-outline-sharp" /></template>
<style>
.l3yrx0tkp {
  fill: currentColor;
  d: path("M11.5 16.5h1v-4h4v-1h-4v-4h-1v4h-4v1h4zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
