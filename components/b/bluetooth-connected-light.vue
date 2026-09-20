<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n61tzdnmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bluetooth-connected-light" /></template>
<style>
.n61tzdnmo {
  fill: currentColor;
  d: path("M195.6 171.2L138 128l57.6-43.2a6 6 0 0 0 0-9.6l-64-48A6 6 0 0 0 122 32v84L67.6 75.2a6 6 0 0 0-7.2 9.6L118 128l-57.6 43.2a6 6 0 0 0 7.2 9.6L122 140v84a6 6 0 0 0 9.6 4.8l64-48a6 6 0 0 0 0-9.6M134 44l48 36l-48 36Zm0 168v-72l48 36Zm-74-74a10 10 0 1 1 10-10a10 10 0 0 1-10 10m154-10a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
