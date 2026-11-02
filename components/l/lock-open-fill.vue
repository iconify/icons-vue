<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uakle1fvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-fill" /></template>
<style>
.uakle1fvz {
  fill: currentColor;
  d: path("M10 6v3h8a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-7a3 3 0 0 1 3-3h2V6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 0 0-3.843-.778A2 2 0 0 0 10 6");
}

</style>
