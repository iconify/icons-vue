<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-qh3tbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-4-fill-round" /></template>
<style>
.a-qh3tbqw {
  fill: currentColor;
  d: path("M20 11.476V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5v-5.524l-.322.286a1 1 0 0 1-1.412-.083l-.013-.015a1 1 0 0 1 .083-1.411l6.342-5.638a5 5 0 0 1 6.644 0l6.342 5.638a1 1 0 0 1 .334.688a1 1 0 0 1-.251.723l-.013.015a1 1 0 0 1-1.412.083ZM13 18a3 3 0 0 0 3-3v-2.435c0-.857-.366-1.673-1.007-2.242l-1-.889a3 3 0 0 0-3.986 0l-1 .889A3 3 0 0 0 8 12.565V15a3 3 0 0 0 3 3Z");
}

</style>
