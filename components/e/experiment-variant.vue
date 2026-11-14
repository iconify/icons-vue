<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op4m4kbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:experiment-variant" /></template>
<style>
.op4m4kbpz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.848 2.848Q2.75 3.947 2.75 5.5q0 3.354 3 3.708V9.5q0 1.945 3.141 3.658q2.359 1.287 2.359 2.342v6q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6q0-1.055 2.359-2.342Q18.25 11.445 18.25 9.5v-.25h.5q2.5 0 2.5-2.5v-2.5q0-2.5-2.5-2.5h-2.5q-2.5 0-2.5 2.5v2.5q0 2.5 2.5 2.5h.5v.25q0 1.055-2.359 2.342q-1.606.876-2.391 1.812q-.785-.936-2.391-1.812Q7.25 10.555 7.25 9.5v-.292q3-.354 3-3.708q0-3.75-3.75-3.75q-1.553 0-2.652 1.098");
}

</style>
