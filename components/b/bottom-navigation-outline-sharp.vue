<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boea9c97w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-navigation-outline-sharp" /></template>
<style>
.boea9c97w {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-4.615h14V5H5zm0 1V19h14v-2.616zm0 0V19z");
}

</style>
