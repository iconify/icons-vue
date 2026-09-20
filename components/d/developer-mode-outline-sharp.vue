<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz9_5bc7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:developer-mode-outline-sharp" /></template>
<style>
.uz9_5bc7l {
  fill: currentColor;
  d: path("M8.6 16.6L4 12l4.6-4.6L10 8.85L6.85 12L10 15.15zM5 17h2v1h10v-1h2v6H5zM7 7H5V1h14v6h-2V6H7zm0 13v1h10v-1zM7 4h10V3H7zm8.4 12.6L14 15.15L17.15 12L14 8.85l1.4-1.45L20 12zM7 4V3zm0 16v1z");
}

</style>
