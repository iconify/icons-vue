<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mioj10btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:blueprint-thin" /></template>
<style>
.mioj10btt {
  fill: currentColor;
  d: path("M232 60H68V40a4 4 0 0 0-4-4H48a28 28 0 0 0-28 28v112a28 28 0 0 0 28 28h184a4 4 0 0 0 4-4V64a4 4 0 0 0-4-4M28 64a20 20 0 0 1 20-20h12v104H48a27.94 27.94 0 0 0-20 8.42Zm200 132H48a20 20 0 0 1 0-40h16a4 4 0 0 0 4-4V68h160Zm-124-56a4 4 0 0 0 0 8h20v12a4 4 0 0 0 8 0v-12h32v12a4 4 0 0 0 8 0v-12h20a4 4 0 0 0 0-8h-20v-24h20a4 4 0 0 0 0-8h-20V96a4 4 0 0 0-8 0v12h-32V96a4 4 0 0 0-8 0v12h-20a4 4 0 0 0 0 8h20v24Zm28-24h32v24h-32Z");
}

</style>
