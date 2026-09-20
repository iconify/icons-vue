<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="it729zb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:git-diff-thin" /></template>
<style>
.it729zb5e {
  fill: currentColor;
  d: path("M112 156a4 4 0 0 0-4 4v38.34l-44.49-44.48a12 12 0 0 1-3.51-8.49V91.71a28 28 0 1 0-8 0v53.66a19.85 19.85 0 0 0 5.86 14.14L102.34 204H64a4 4 0 0 0 0 8h48a4 4 0 0 0 4-4v-48a4 4 0 0 0-4-4M36 64a20 20 0 1 1 20 20a20 20 0 0 1-20-20m168 100.29v-53.66a19.85 19.85 0 0 0-5.86-14.14L153.66 52H192a4 4 0 0 0 0-8h-48a4 4 0 0 0-4 4v48a4 4 0 0 0 8 0V57.66l44.49 44.48a12 12 0 0 1 3.51 8.49v53.66a28 28 0 1 0 8 0M200 212a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

</style>
