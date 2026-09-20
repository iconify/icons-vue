<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzrnb1mnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-top-24-filled" /></template>
<style>
.fzrnb1mnw {
  fill: currentColor;
  d: path("M2.75 3a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5zM4 8.25A2.25 2.25 0 0 1 6.25 6h2.5A2.25 2.25 0 0 1 11 8.25v10.5A2.25 2.25 0 0 1 8.75 21h-2.5A2.25 2.25 0 0 1 4 18.75zm9 0A2.25 2.25 0 0 1 15.25 6h2.5A2.25 2.25 0 0 1 20 8.25v7a2.25 2.25 0 0 1-2.25 2.25h-2.5A2.25 2.25 0 0 1 13 15.25z");
}

</style>
