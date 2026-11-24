<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z55qg0bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:corner-regular-fill-sharp" /></template>
<style>
.z55qg0bll {
  fill: currentColor;
  d: path("M4 12a8 8 0 0 1 8-8h7a1 1 0 0 1 0 2h-7a6 6 0 0 0-6 6v7a1 1 0 0 1-2 0Z");
}

</style>
