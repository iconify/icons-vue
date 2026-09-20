<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8q12bo5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-square-outline-sharp" /></template>
<style>
.e8q12bo5p {
  fill: currentColor;
  d: path("M4 20V4h10.002l-1 1H5v14h14v-8.104l1-1V20zm6-6v-2.615l9.664-9.664l2.597 2.525L12.52 14zm10.814-9.715l-1.112-1.17zM11 13h1.092l6.666-6.666l-.546-.546l-.61-.584L11 11.806zm7.212-7.211l-.61-.585zl.546.546z");
}

</style>
