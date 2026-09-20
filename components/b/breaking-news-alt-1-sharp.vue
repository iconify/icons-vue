<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfeygflxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news-alt-1-sharp" /></template>
<style>
.vfeygflxl {
  fill: currentColor;
  d: path("M6.77 16.5h4.46v-1H6.77zm9.46 0h1v-1h-1zm-9.46-4h4.46v-1H6.77zm9.46 0h1v-5h-1zm-9.46-4h4.46v-1H6.77zM3 20V4h18v16z");
}

</style>
