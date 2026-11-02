<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1kzf5lcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-fill-sharp" /></template>
<style>
.f1kzf5lcr {
  fill: currentColor;
  d: path("M6 4a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v15h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-5c0-.265.105-.52.293-.707L6 11.586Zm3.293 4.293a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 16 14v5h2V5H8v4.586Z");
}

</style>
