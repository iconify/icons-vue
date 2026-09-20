<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="umtf7h7oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hourglass-simple-medium-bold" /></template>
<style>
.umtf7h7oi {
  fill: currentColor;
  d: path("M214 193.68L145.35 128L214 62.32l.18-.18A20 20 0 0 0 200 28H56a20 20 0 0 0-14.13 34.14l.18.18l68.6 65.68l-68.6 65.68l-.18.18A20 20 0 0 0 56 228h144a20 20 0 0 0 14.14-34.14ZM107.75 92h40.5L128 111.39ZM190 52l-16.69 16H82.69L66 52ZM66 204l50-47.9V168a12 12 0 0 0 24 0v-11.9l50 47.9Z");
}

</style>
