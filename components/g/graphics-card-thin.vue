<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h8-g3ybea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:graphics-card-thin" /></template>
<style>
.h8-g3ybea {
  fill: currentColor;
  d: path("M232 52H16a4 4 0 0 0-4 4v152a4 4 0 0 0 8 0v-20h24v20a4 4 0 0 0 8 0v-20h24v20a4 4 0 0 0 8 0v-20h24v20a4 4 0 0 0 8 0v-20h116a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m4 124a4 4 0 0 1-4 4H20V60h212a4 4 0 0 1 4 4Zm-60-92a36 36 0 1 0 36 36a36 36 0 0 0-36-36m-28 36a27.9 27.9 0 0 1 5.58-16.76l39.18 39.18A28 28 0 0 1 148 120m50.42 16.76l-39.18-39.18a28 28 0 0 1 39.18 39.18M80 84a36 36 0 1 0 36 36a36 36 0 0 0-36-36m-28 36a27.9 27.9 0 0 1 5.58-16.76l39.18 39.18A28 28 0 0 1 52 120m50.42 16.76L63.24 97.58a28 28 0 0 1 39.18 39.18");
}

</style>
