<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnnbb8hlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home" /></template>
<style>
.wnnbb8hlj {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12h-6v-7h-4v7z");
}

</style>
