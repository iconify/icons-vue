<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryof_6pvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-panel-open-outline-sharp" /></template>
<style>
.ryof_6pvt {
  fill: currentColor;
  d: path("M8.827 11.596h6.346L12 8.404zM5 19h14v-3H5zm0-4h14V5H5zm0 1v3zm-1 4V4h16v16z");
}

</style>
