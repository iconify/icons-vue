<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1sr06b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-9-16-outline-sharp" /></template>
<style>
.m1sr06b6h {
  fill: currentColor;
  d: path("M8 20V4h8v16zM9 5v14h6V5zm0 14V5z");
}

</style>
