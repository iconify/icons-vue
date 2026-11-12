<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nstse8s_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-burndown-fill-sharp" /></template>
<style>
.nstse8s_d {
  fill: currentColor;
  d: path("M4 4v15h15.382l-3-6H14a1 1 0 0 1-.857-.486L10.434 8H7a1 1 0 0 1 0-2h4c.351 0 .677.184.857.486L14.566 11H17c.379 0 .725.214.894.553l4 8A1 1 0 0 1 21 21H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0");
}

</style>
