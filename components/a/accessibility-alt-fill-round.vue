<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3nw3btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:accessibility-alt-fill-round" /></template>
<style>
.oj3nw3btd {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 5M5 9h14a1 1 0 0 1 0 2h-6v2.697l3.832 5.748a1 1 0 0 1-1.664 1.11L12 15.803l-3.168 4.752a1 1 0 0 1-1.664-1.11L11 13.697V11H5a1 1 0 0 1 0-2");
}

</style>
