<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5cq1dvou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bucket-check-outline-sharp" /></template>
<style>
.s5cq1dvou {
  fill: currentColor;
  d: path("M5.75 20L4 7.385h2.77V4h10.46v3.385H20L18.23 20zm.879-1H17.37l1.464-10.615H5.145zm4.36-2.923l4.065-4.027l-.713-.688l-3.333 3.294l-1.348-1.329l-.714.714zm-3.22-8.693h8.462V5H7.769zM12 13.692");
}

</style>
