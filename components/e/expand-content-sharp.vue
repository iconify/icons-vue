<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7q4fxgdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expand-content-sharp" /></template>
<style>
.e7q4fxgdu {
  fill: currentColor;
  d: path("M6 18v-5h1v4h4v1zm11-7V7h-4V6h5v5z");
}

</style>
