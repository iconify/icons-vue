<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvrfndvrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dock-to-bottom-outline-sharp" /></template>
<style>
.rvrfndvrn {
  fill: currentColor;
  d: path("M5 19h14v-3H5zm0-4h14V5H5zm0 1v3zm-1 4V4h16v16z");
}

</style>
