<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0hcb7_fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dishwasher-gen-sharp" /></template>
<style>
.z0hcb7_fp {
  fill: currentColor;
  d: path("M8 6.77q.31 0 .54-.23T8.77 6t-.23-.54T8 5.23t-.54.23t-.23.54t.23.54t.54.23m3.54-.23q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M12 17.5q1.364 0 2.332-.93t.968-2.27q0-.629-.212-1.22q-.211-.591-.653-1.034L12 9.612l-2.354 2.353q-.473.473-.722 1.077T8.7 14.3q.05 1.339 1.006 2.27T12 17.5m-1.63-1.579q-.67-.66-.67-1.621q0-.452.147-.857t.48-.737L12 11.033l1.744 1.744q.295.294.425.702q.131.408.131.821q0 .962-.67 1.621q-.668.66-1.63.66t-1.63-.66M5 21V3h14v18z");
}

</style>
