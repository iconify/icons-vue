<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b77a-o8tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ambulance-fill-round" /></template>
<style>
.b77a-o8tm {
  fill: currentColor;
  d: path("M13.874 7H16c1.039 0 1.992.578 2.707 1.293l2 2C21.422 11.008 22 11.961 22 13v3c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16V9a5 5 0 0 1 5-5h3a4.006 4.006 0 0 1 3.874 3M9 10V9a1 1 0 0 0-2 0v1H6a1 1 0 0 0 0 2h1v1a1 1 0 0 0 2 0v-1h1a1 1 0 0 0 0-2Zm5 2h5.586l-2.707-2.707A1 1 0 0 0 16.172 9H14Zm-7.709 6.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
