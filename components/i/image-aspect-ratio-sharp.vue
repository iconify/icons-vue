<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w44bdulww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-aspect-ratio-sharp" /></template>
<style>
.w44bdulww {
  fill: currentColor;
  d: path("M6 12h2v-2H6zm4 0h2v-2h-2zm4 4h2v-2h-2zm0-4h2v-2h-2zM2 20V4h20v16z");
}

</style>
