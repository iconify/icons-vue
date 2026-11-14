<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpkbvxbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-bottle-warmer" /></template>
<style>
.rpkbvxbfx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 4.5v.75q-2 0-2 2q0 1 .5 1.5V16q0 2.75 2.75 2.75h3q2.75 0 2.75-2.75V8.75q.5-.5.5-1.5q0-2-2-2V4.5q0-2.75-2.75-2.75T9.25 4.5m1.5 0v.75h2.5V4.5q0-1.25-1.25-1.25T10.75 4.5m-1.5 4.75h5.5V16q0 1.25-1.25 1.25h-3q-1.25 0-1.25-1.25zM5.75 11v7q0 1.139.805 1.945q.806.805 1.945.805h7q1.139 0 1.945-.805q.805-.806.805-1.945v-7q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7q0 1.76-1.245 3.005T15.5 22.25h-7q-1.76 0-3.005-1.245T4.25 18v-7q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5 10.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
