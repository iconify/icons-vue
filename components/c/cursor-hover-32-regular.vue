<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wek8hib5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-hover-32-regular" /></template>
<style>
.wek8hib5a {
  fill: currentColor;
  d: path("M2 10a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4v10a4 4 0 0 1-2.328 3.635a3 3 0 0 0-.55-.756l-.892-.892A2 2 0 0 0 28 20V10a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h8v2H6a4 4 0 0 1-4-4zm15.707 6.293A1 1 0 0 0 16 17v12a1 1 0 0 0 1.8.6l2.7-3.6H25a1 1 0 0 0 .707-1.707zM18 26v-6.586L22.586 24H20a1 1 0 0 0-.8.4z");
}

</style>
