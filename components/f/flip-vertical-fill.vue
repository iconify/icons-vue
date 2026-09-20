<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j52oefodz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flip-vertical-fill" /></template>
<style>
.j52oefodz {
  fill: currentColor;
  d: path("M56 120h160a16 16 0 0 0 6.23-30.74l-.14-.06l-159.93-64A16 16 0 0 0 40 40v64a16 16 0 0 0 16 16m0-80l.15.06L216 104H56zm175.67 108.82a15.85 15.85 0 0 1-9.45 17.92l-.14.06l-159.93 64A16 16 0 0 1 40 216v-64a16 16 0 0 1 16-16h160a15.85 15.85 0 0 1 15.67 12.82");
}

</style>
