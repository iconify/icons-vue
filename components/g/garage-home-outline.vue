<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9dhaqekf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-home-outline" /></template>
<style>
.j9dhaqekf {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.288L19 9.5V20h-1V10l-6-4.538L6 10v10zm3.5-1.02h7v-3h-7zm0-4h7v-3h-7zm-1 5v-9h9v9z");
}

</style>
