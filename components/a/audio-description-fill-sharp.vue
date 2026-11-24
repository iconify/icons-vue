<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwi-je9oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:audio-description-fill-sharp" /></template>
<style>
.iwi-je9oy {
  fill: currentColor;
  d: path("M19.8 5.4A10.97 10.97 0 0 1 22 12a11 11 0 0 1-.55 3.437A10.9 10.9 0 0 1 19.8 18.6a1 1 0 0 1-1.6-1.2A8.96 8.96 0 0 0 20 12a8.97 8.97 0 0 0-1.8-5.4a1.002 1.002 0 0 1 .68-1.593a1 1 0 0 1 .92.393M2 16v-5a4 4 0 0 1 8 0v5a1 1 0 0 1-2 0v-2H4v2a1 1 0 0 1-2 0m12-9a5 5 0 0 1 0 10h-1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Zm-6 5v-1a2 2 0 1 0-4 0v1Zm6-3v6a3 3 0 1 0 0-6");
}

</style>
