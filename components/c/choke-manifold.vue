<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzi7qce7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:choke-manifold" /></template>
<style>
.lzi7qce7s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.25q-3.75 0-3.75 3.749v.002q0 1.874.938 2.812q.739.739 2.062.895v1.542h-2.5q-2.5 0-2.5 2.5v.5q0 1.036.732 1.768t1.768.732h6v5.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5.75h1.5v5.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5.75h6q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768t-1.768-.732h-2.5V8.708q3-.354 3-3.708q0-3.75-3.75-3.75T13.25 5q0 3.354 3 3.708v1.542h-8.5V8.708q3-.354 3-3.708q0-3.75-3.75-3.75");
}

</style>
