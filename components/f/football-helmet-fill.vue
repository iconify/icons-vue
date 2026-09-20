<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m_tt_hbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:football-helmet-fill" /></template>
<style>
.m_tt_hbuh {
  fill: currentColor;
  d: path("M216 160h-50.2l-7.09-24H216a8 8 0 0 0 8-8v-4A100 100 0 0 0 122.58 24C68.24 24.77 24 69.61 24 124a100 100 0 0 0 43.62 82.6a8 8 0 0 0 4.52 1.4H120a16 16 0 0 0 15.62-19.47a5 5 0 0 0-.15-.54l-3.56-12h21.93l10.79 36.53A16.1 16.1 0 0 0 180 224h36a16 16 0 0 0 16-16v-32a16 16 0 0 0-16-16M84 176a12 12 0 1 1 12-12a12 12 0 0 1-12 12m43.16-16L120 136h22l7.09 24ZM216 208h-36l-9.46-32H216Z");
}

</style>
