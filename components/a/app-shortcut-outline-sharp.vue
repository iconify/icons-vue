<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9byrbbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:app-shortcut-outline-sharp" /></template>
<style>
.k9byrbbsc {
  fill: currentColor;
  d: path("M17.15 13H12v3h-2v-5h7.15L15.6 9.4L17 8l4 4l-4 4l-1.4-1.4zM5 23V1h14v6h-2V6H7v12h10v-1h2v6zm2-3v1h10v-1zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
