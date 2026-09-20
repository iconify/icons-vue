<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr97m0b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:aspect-ratio-sharp" /></template>
<style>
.tr97m0b_u {
  fill: currentColor;
  d: path("M14 17h5v-5h-2v3h-3zm-9-5h2V9h3V7H5zm-3 8V4h20v16z");
}

</style>
