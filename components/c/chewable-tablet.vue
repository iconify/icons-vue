<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpb6eob5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chewable-tablet" /></template>
<style>
.xpb6eob5p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.96 3.492q.022-.066.032-.135t.007-.139q-.003-.069-.018-.137q-.016-.068-.044-.132t-.067-.121t-.089-.107t-.106-.089q-.058-.04-.121-.068q-3.939-1.743-7.722.314T3.371 9.189q-.153.96-.121 1.862V13.5q0 3.624 2.563 6.187T12 22.25t6.187-2.563T20.75 13.5v-1.883q.248-2.015-.548-4.131q-.024-.065-.061-.125q-.036-.059-.082-.111t-.102-.095q-.055-.042-.117-.074t-.129-.051t-.136-.026q-.07-.007-.139-.001q-.07.006-.137.024q-1.597.444-2.735-.761t-.604-2.774M6.873 18.627Q5.717 17.47 5.19 16.053q.218.264.46.52q2.958 3.131 7.242 2.698q3.693-.374 5.889-3.143q-.529 1.373-1.654 2.499Q15.003 20.75 12 20.75t-5.127-2.123");
}

</style>
