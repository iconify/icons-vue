<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4kg-gh5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dock-to-right-outline-sharp" /></template>
<style>
.q4kg-gh5g {
  fill: currentColor;
  d: path("M5 19h3V5H5zm5 0h9V5h-9zm-2 0H5zm-5 2V3h18v18z");
}

</style>
