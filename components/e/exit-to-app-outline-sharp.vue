<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ai9n91c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:exit-to-app-outline-sharp" /></template>
<style>
.y4ai9n91c {
  fill: currentColor;
  d: path("M3 21v-6h2v4h14V5H5v4H3V3h18v18zm7.5-4l-1.4-1.45L11.65 13H3v-2h8.65L9.1 8.45L10.5 7l5 5z");
}

</style>
