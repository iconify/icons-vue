<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubmnd0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dock-to-left-sharp" /></template>
<style>
.ubmnd0bhf {
  fill: currentColor;
  d: path("M5 19h10V5H5zm-1 1V4h16v16z");
}

</style>
