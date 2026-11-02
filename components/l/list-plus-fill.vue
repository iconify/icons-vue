<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn8qimbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-plus-fill" /></template>
<style>
.rn8qimbrb {
  fill: currentColor;
  d: path("M3 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m16 2v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0M3 15h7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
