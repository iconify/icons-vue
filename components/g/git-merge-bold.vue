<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g1cgyz6gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:git-merge-bold" /></template>
<style>
.g1cgyz6gq {
  fill: currentColor;
  d: path("M208 108a36.05 36.05 0 0 0-33.38 22.54l-39-5.57a4 4 0 0 1-2.47-1.35l-32.6-38.09A36 36 0 1 0 68 89.94v76.12a36 36 0 1 0 24 0v-53.62l23 26.8a28 28 0 0 0 17.3 9.49l41.34 5.91A36 36 0 1 0 208 108M80 44a12 12 0 1 1-12 12a12 12 0 0 1 12-12m0 168a12 12 0 1 1 12-12a12 12 0 0 1-12 12m128-56a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
