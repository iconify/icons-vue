<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya2--l60b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ad-sharp" /></template>
<style>
.ya2--l60b {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V8H5z");
}

</style>
