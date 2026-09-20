<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyh_zvvft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:close-fullscreen-outline" /></template>
<style>
.nyh_zvvft {
  fill: currentColor;
  d: path("M3.689 21L3 20.312L10.312 13H5v-1h7v7h-1v-5.312zM12 12V5h1v5.312L20.312 3l.688.688L13.688 11H19v1z");
}

</style>
