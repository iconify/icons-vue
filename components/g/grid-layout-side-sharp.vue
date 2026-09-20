<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_nf5wbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:grid-layout-side-sharp" /></template>
<style>
.g_nf5wbbo {
  fill: currentColor;
  d: path("M20 20V4zM4 20h9.5V4H4zm16 0V4h-5.5v16z");
}

</style>
