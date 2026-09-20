<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8b3xebcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-awesome-mosaic-sharp" /></template>
<style>
.z8b3xebcf {
  fill: currentColor;
  d: path("M11 20H4V4h7zm2-9V4h7v7zm0 9v-7h7v7z");
}

</style>
