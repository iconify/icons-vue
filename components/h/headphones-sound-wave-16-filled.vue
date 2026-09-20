<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9qqcfo8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-sound-wave-16-filled" /></template>
<style>
.t9qqcfo8x {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7v4.5a2.5 2.5 0 0 1-2.5 2.5a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 .5-.5H14V8A6 6 0 0 0 2 8v1h1.5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5a2.5 2.5 0 0 1-2.487-2.244L1 12.5V8a7 7 0 0 1 7-7m0 6.5a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V8a.5.5 0 0 1 .5-.5M5.5 9a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0v-3a.5.5 0 0 1 .5-.5m5 0a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-1 0v-3a.5.5 0 0 1 .5-.5");
}

</style>
