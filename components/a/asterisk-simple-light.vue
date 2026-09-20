<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oma01mben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:asterisk-simple-light" /></template>
<style>
.oma01mben {
  fill: currentColor;
  d: path("m210.23 101.57l-72.6 29l51.11 65.71a6 6 0 0 1-9.48 7.36L128 137.77l-51.26 65.91a6 6 0 1 1-9.48-7.36l51.11-65.71l-72.6-29a6 6 0 1 1 4.46-11.14L122 119.14V40a6 6 0 0 1 12 0v79.14l71.77-28.71a6 6 0 1 1 4.46 11.14");
}

</style>
