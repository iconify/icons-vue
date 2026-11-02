<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg3p42byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-j-bulk-sharp" /></template>
<style>
.lg3p42byb {
  fill: currentColor;
  d: path("M18 16a6 6 0 1 1-12 0a1 1 0 0 1 2 0a3.95 3.95 0 0 0 .314 1.557A4 4 0 0 0 16 16V4a1 1 0 0 1 2 0Z");
}

</style>
