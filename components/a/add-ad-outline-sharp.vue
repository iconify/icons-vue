<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baxr85b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-ad-outline-sharp" /></template>
<style>
.baxr85b4q {
  fill: currentColor;
  d: path("M18 20v-3h-3v-2h3v-3h2v3h3v2h-3v3zM1 21V3h18v7h-2V8H3v11h13v2zM3 6h14V5H3zm0 0V5z");
}

</style>
