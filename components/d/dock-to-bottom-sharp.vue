<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1do82chx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dock-to-bottom-sharp" /></template>
<style>
.i1do82chx {
  fill: currentColor;
  d: path("M5 15h14V5H5zm-1 5V4h16v16z");
}

</style>
