<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w09y9dbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-gemini" /></template>
<style>
.w09y9dbkv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C24 14.374 14.374 24 2.5 24M24 45.5C24 33.626 14.374 24 2.5 24M24 2.5C24 14.374 33.626 24 45.5 24M24 45.5C24 33.626 33.626 24 45.5 24");
}

</style>
