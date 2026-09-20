<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v8pp1mbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:eject-fill" /></template>
<style>
.v8pp1mbls {
  fill: currentColor;
  d: path("M33.31 126.24a15.59 15.59 0 0 1 3.1-17.12l73.73-77.51a24.76 24.76 0 0 1 35.72 0l73.73 77.51a15.59 15.59 0 0 1 3.1 17.12a16.18 16.18 0 0 1-14.93 9.76H48.24a16.18 16.18 0 0 1-14.93-9.76M208 152H48a16 16 0 0 0-16 16v16a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16v-16a16 16 0 0 0-16-16");
}

</style>
