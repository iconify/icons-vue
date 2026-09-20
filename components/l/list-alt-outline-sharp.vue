<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv4w0y2uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-alt-outline-sharp" /></template>
<style>
.nv4w0y2uv {
  fill: currentColor;
  d: path("M7.346 16.539h1.539V15H7.346zm0-3.77h1.539v-1.538H7.346zm0-3.769h1.539V7.462H7.346zm3.846 7.27h5.385v-1h-5.385zm0-3.77h5.385v-1h-5.385zm0-3.77h5.385v-1h-5.385zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
