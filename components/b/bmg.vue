<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shuo4jq6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bmg" /></template>
<style>
.shuo4jq6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 4.49c1.108 0 2 .892 2 2v20a4 4 0 0 1-4 4h-7c-1.108 0-2-.891-2-2v-16a8 8 0 0 1 8-8zm3.992 13.304C32.226 18.752 37 24.14 37 30.642s-4.774 11.89-11.008 12.848c-1.09.167-1.992-.744-1.992-1.849v-22c0-1.104.901-2.016 1.992-1.848z");
}

</style>
