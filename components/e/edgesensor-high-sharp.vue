<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4pdidbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edgesensor-high-sharp" /></template>
<style>
.a4pdidbgn {
  fill: currentColor;
  d: path("M6.808 20V4h10.384v16zm5.78-11.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M1.462 16.5v-6h1v6zm2.769-3v-6h1v6zm17.307 0v-6h1v6zm-2.769 3v-6h1v6z");
}

</style>
