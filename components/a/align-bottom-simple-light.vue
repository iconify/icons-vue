<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jtmyseb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-bottom-simple-light" /></template>
<style>
.jtmyseb8a {
  fill: currentColor;
  d: path("M206 232a6 6 0 0 1-6 6H56a6 6 0 0 1 0-12h144a6 6 0 0 1 6 6M82 192V40a14 14 0 0 1 14-14h64a14 14 0 0 1 14 14v152a14 14 0 0 1-14 14H96a14 14 0 0 1-14-14m12 0a2 2 0 0 0 2 2h64a2 2 0 0 0 2-2V40a2 2 0 0 0-2-2H96a2 2 0 0 0-2 2Z");
}

</style>
