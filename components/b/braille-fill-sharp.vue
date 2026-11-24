<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx8vjq-2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:braille-fill-sharp" /></template>
<style>
.kx8vjq-2k {
  fill: currentColor;
  d: path("M6 4a2 2 0 1 1 3.999-.001A2 2 0 0 1 6 4m10.01-1a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2ZM14 12a2 2 0 1 1 3.999-.001A2 2 0 0 1 14 12m-5.99-1a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM6 20a2 2 0 1 1 3.999-.001A2 2 0 0 1 6 20m10.01-1a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Z");
}

</style>
