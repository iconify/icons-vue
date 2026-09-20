<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hh6pscc-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:globe-stand-20-filled" /></template>
<style>
.hh6pscc-a {
  fill: currentColor;
  d: path("M17.5 10a.5.5 0 0 1 0 1h-.572a7 7 0 0 1-5.36 5.82c.757-1.242 1.292-3.357 1.408-5.82h-1.003c-.084 1.708-.376 3.207-.788 4.306c-.22.587-.46 1.019-.685 1.304V18h2a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1h2v-1.39c-.225-.285-.464-.717-.685-1.304c-.412-1.1-.704-2.598-.788-4.306H7.024c.116 2.463.65 4.578 1.408 5.82A7 7 0 0 1 3.072 11H2.5a.5.5 0 0 1 0-1zM8.432 3.179C7.674 4.42 7.14 6.537 7.024 9H3.072a7 7 0 0 1 5.36-5.821M10 1a.5.5 0 0 1 .5.5v1.889c.226.285.464.718.685 1.305c.412 1.1.704 2.598.788 4.306H8.027c.084-1.708.376-3.206.788-4.306c.22-.587.46-1.02.685-1.305V1.5A.5.5 0 0 1 10 1m1.567 2.179A7 7 0 0 1 16.927 9h-3.951c-.116-2.464-.65-4.58-1.409-5.821");
}

</style>
