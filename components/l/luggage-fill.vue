<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4b5w5bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-fill" /></template>
<style>
.j4b5w5bej {
  fill: currentColor;
  d: path("M8 6V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2h1a3 3 0 0 1 3 3v8c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128h-.342a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 4 17V9a3 3 0 0 1 3-3Zm6-2h-4v2h4ZM9.705 19.709l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 1 0 0 1.418m4.588-.002l.002.002a1 1 0 1 0 0-1.418l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

</style>
