<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7g59fbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:local-bar" /></template>
<style>
.x7g59fbsb {
  fill: currentColor;
  d: path("M21 5V3H3v2l8 9v5H6v2h12v-2h-5v-5zM7.43 7L5.66 5h12.69l-1.78 2z");
}

</style>
