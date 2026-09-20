<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="copnfh97o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-counter-clockwise-thin" /></template>
<style>
.copnfh97o {
  fill: currentColor;
  d: path("M220 128a92 92 0 0 1-90.77 92H128a91.47 91.47 0 0 1-63.13-25.1a4 4 0 1 1 5.5-5.82A84 84 0 1 0 68.6 68.57l-.13.12L34.3 100H72a4 4 0 0 1 0 8H24a4 4 0 0 1-4-4V56a4 4 0 0 1 8 0v38.89l35-32A92 92 0 0 1 220 128");
}

</style>
