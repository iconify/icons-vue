<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ppf8b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dock-to-bottom-outline-sharp" /></template>
<style>
.i3ppf8b7z {
  fill: currentColor;
  d: path("M5 19h14v-3H5zm0-5h14V5H5zm0 2v3zm-2 5V3h18v18z");
}

</style>
