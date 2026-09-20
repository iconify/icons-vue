<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlamumbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-sheets-sharp" /></template>
<style>
.xlamumbqb {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-9h14V5H5z");
}

</style>
