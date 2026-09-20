<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boe5rbb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-file-sharp" /></template>
<style>
.boe5rbb4g {
  fill: currentColor;
  d: path("M10.75 19q.95 0 1.6-.65t.65-1.6V13h3v-2h-4v3.875q-.275-.2-.587-.288t-.663-.087q-.95 0-1.6.65t-.65 1.6t.65 1.6t1.6.65M4 22V2h10l6 6v14zm9-13h5l-5-5z");
}

</style>
