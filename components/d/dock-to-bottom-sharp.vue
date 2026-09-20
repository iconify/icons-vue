<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3h7vebmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dock-to-bottom-sharp" /></template>
<style>
.e3h7vebmw {
  fill: currentColor;
  d: path("M5 14h14V5H5zm-2 7V3h18v18z");
}

</style>
