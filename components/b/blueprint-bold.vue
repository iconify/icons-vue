<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a1g33eb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:blueprint-bold" /></template>
<style>
.a1g33eb2w {
  fill: currentColor;
  d: path("M232 48H76v-8a12 12 0 0 0-12-12H48a36 36 0 0 0-36 36v112a36 36 0 0 0 36 36h184a12 12 0 0 0 12-12V60a12 12 0 0 0-12-12M36 64a12 12 0 0 1 12-12h4v88h-4a35.6 35.6 0 0 0-12 2.06Zm184 124H48a12 12 0 0 1 0-24h16a12 12 0 0 0 12-12V72h144Zm-116-52a12 12 0 0 0 0 24h12v4a12 12 0 0 0 24 0v-4h16v4a12 12 0 0 0 24 0v-4h12a12 12 0 0 0 0-24h-12v-12h12a12 12 0 0 0 0-24h-12v-4a12 12 0 0 0-24 0v4h-16v-4a12 12 0 0 0-24 0v4h-12a12 12 0 0 0 0 24h12v12Zm36-12h16v12h-16Z");
}

</style>
