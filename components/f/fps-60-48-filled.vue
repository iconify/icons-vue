<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ncd3h65up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fps-60-48-filled" /></template>
<style>
.ncd3h65up {
  fill: currentColor;
  d: path("M30 6a6 6 0 0 0-6 6v8a6 6 0 0 0 12 0v-8a6 6 0 0 0-6-6m3 14a3 3 0 1 1-6 0v-8a3 3 0 1 1 6 0zM8 31.25c0-.69.56-1.25 1.25-1.25h6.506a1.25 1.25 0 1 1 0 2.5H10.5V36h4.25a1.25 1.25 0 1 1 0 2.5H10.5v4.29a1.25 1.25 0 1 1-2.5 0zM20.75 30c-.69 0-1.25.56-1.25 1.25v11.54a1.25 1.25 0 1 0 2.5 0V38.5h2.25a4.25 4.25 0 0 0 0-8.5zm3.5 6H22v-3.5h2.25a1.75 1.75 0 1 1 0 3.5M33 34.156c0-.915.741-1.656 1.656-1.656h1.594c.69 0 1.25.56 1.25 1.25a1.25 1.25 0 1 0 2.5 0A3.75 3.75 0 0 0 36.25 30h-1.594a4.156 4.156 0 1 0 0 8.311h1.25a1.595 1.595 0 0 1 0 3.189H34.25c-.69 0-1.25-.56-1.25-1.25a1.25 1.25 0 1 0-2.5 0A3.75 3.75 0 0 0 34.25 44h1.656a4.094 4.094 0 1 0 0-8.189h-1.25A1.656 1.656 0 0 1 33 34.156M13 12a3 3 0 1 1 6 0a1.5 1.5 0 0 0 3 0a6 6 0 0 0-12 0v8.25q0 .126.02.248A6 6 0 1 0 13 14.803zm0 8a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
