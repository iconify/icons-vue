<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qb9kevbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chalkboard-bold" /></template>
<style>
.qb9kevbkg {
  fill: currentColor;
  d: path("M240 188h-4V56a20 20 0 0 0-20-20H40a20 20 0 0 0-20 20v132h-4a12 12 0 0 0 0 24h224a12 12 0 0 0 0-24M44 60h168v128h-16v-28a12 12 0 0 0-12-12h-64a12 12 0 0 0-12 12v28H84v-88h88v20a12 12 0 0 0 24 0V88a12 12 0 0 0-12-12H72a12 12 0 0 0-12 12v100H44Zm128 128h-40v-16h40Z");
}

</style>
