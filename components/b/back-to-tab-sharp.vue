<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6g6ysbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:back-to-tab-sharp" /></template>
<style>
.y6g6ysbzp {
  fill: currentColor;
  d: path("M9.525 12.239L4 6.714v3.902H3V5h5.616v1H4.689l5.55 5.525zM3 19v-6h1v5h7.77v1zm17-6.23V6h-9V5h10v7.77zm1 2.384V19h-6.846v-3.846z");
}

</style>
