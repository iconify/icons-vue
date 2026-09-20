<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o51r2vbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-outline-sharp" /></template>
<style>
.o51r2vbay {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4h-2v7l-2.5-1.5L11 11V4H6zm0 0V4zm5-9l2.5-1.5L16 11l-2.5-1.5z");
}

</style>
