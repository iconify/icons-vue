<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4xovguxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ad-sharp" /></template>
<style>
.x4xovguxz {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V8.154H5z");
}

</style>
