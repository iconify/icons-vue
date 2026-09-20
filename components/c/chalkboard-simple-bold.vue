<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i02_mn6da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chalkboard-simple-bold" /></template>
<style>
.i02_mn6da {
  fill: currentColor;
  d: path("M240 188h-4v-28a12 12 0 0 0-12-12h-64a12 12 0 0 0-12 12v28H44V60h168v60a12 12 0 0 0 24 0V56a20 20 0 0 0-20-20H40a20 20 0 0 0-20 20v132h-4a12 12 0 0 0 0 24h224a12 12 0 0 0 0-24m-68-16h40v16h-40Z");
}

</style>
