<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7i1a65zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dishwasher-gen-rounded" /></template>
<style>
.h7i1a65zq {
  fill: currentColor;
  d: path("M8 6.77q.31 0 .54-.23T8.77 6t-.23-.54T8 5.23t-.54.23t-.23.54t.23.54t.54.23m3.54-.23q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M12 17.5q1.364 0 2.332-.93t.968-2.27q0-.629-.212-1.22q-.211-.591-.653-1.034l-1.87-1.869q-.242-.242-.565-.242t-.565.242l-1.789 1.789q-.473.473-.722 1.076T8.7 14.3q.05 1.339 1.006 2.27T12 17.5m-1.63-1.579q-.67-.66-.67-1.621q0-.452.147-.857t.48-.737L12 11.033l1.744 1.744q.295.294.425.702q.131.408.131.821q0 .962-.67 1.621q-.668.66-1.63.66t-1.63-.66M6.615 21q-.672 0-1.144-.472T5 19.385V4.615q0-.67.472-1.143Q5.944 3 6.616 3h10.769q.67 0 1.143.472q.472.472.472 1.144v14.769q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
