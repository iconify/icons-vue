<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsqzvdndj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-add-sharp" /></template>
<style>
.lsqzvdndj {
  fill: currentColor;
  d: path("M13 14h2v-3h3V9h-3V6h-2v3h-3v2h3zm-7 4V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
