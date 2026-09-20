<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnj3-ckvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:frame-exclamation-outline-sharp" /></template>
<style>
.nnj3-ckvx {
  fill: currentColor;
  d: path("M11 14V5h2v9zm0 5v-2h2v2zM1 23v-5h2v3h3v2zm17 0v-2h3v-3h2v5zM1 6V1h5v2H3v3zm20 0V3h-3V1h5v5z");
}

</style>
