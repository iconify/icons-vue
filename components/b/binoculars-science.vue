<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znq5qockq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:binoculars-science" /></template>
<style>
.znq5qockq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 15.5V7q0-1.139.805-1.945q.806-.805 1.945-.805h4q2.75 0 2.75 2.75v1.25h1.5V7q0-2.75 2.75-2.75h4q2.75 0 2.75 2.75v8.5q0 1.968-1.391 3.359T17.5 20.25t-3.359-1.391T12.75 15.5V9.75h-1.5v5.75q0 1.968-1.391 3.359T6.5 20.25t-3.359-1.391T1.75 15.5m8-8.5q0-1.25-1.25-1.25h-4q-.518 0-.884.366T3.25 7v5.035Q4.609 10.75 6.5 10.75t3.25 1.285zm4.5 5.035q1.359-1.285 3.25-1.285t3.25 1.285V7q0-1.25-1.25-1.25h-4q-1.25 0-1.25 1.25z");
}

</style>
