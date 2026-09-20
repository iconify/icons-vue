<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdgje-blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-right-48-regular" /></template>
<style>
.gdgje-blf {
  fill: currentColor;
  d: path("M16.116 39.634a1.25 1.25 0 0 1 0-1.768L29.982 24L16.116 10.134a1.25 1.25 0 0 1 1.768-1.768l14.75 14.75a1.25 1.25 0 0 1 0 1.768l-14.75 14.75a1.25 1.25 0 0 1-1.768 0");
}

</style>
