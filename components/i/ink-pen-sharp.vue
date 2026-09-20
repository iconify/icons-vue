<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faoxljbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-pen-sharp" /></template>
<style>
.faoxljbye {
  fill: currentColor;
  d: path("m13.948 12.533l-2.327-2.352l4.083-4.077l-.821-.821l-5.34 5.34l-.708-.67l6.067-6.066l1.51 1.51l1.397-1.399l2.347 2.346zM6.462 20H4.135v-2.327l6.754-6.76l2.352 2.328z");
}

</style>
