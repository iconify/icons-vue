<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsa460rmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:encryption" /></template>
<style>
.xsa460rmc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.263 1.798l8 3q.108.04.198.11t.155.165t.1.203q.034.109.034.224v6q0 7.402-8.478 10.699q-.131.051-.272.051t-.272-.051Q3.25 18.902 3.25 11.5v-6q0-.115.034-.224t.1-.203q.065-.094.155-.165q.09-.07.198-.11l8-3q.127-.048.263-.048t.263.048M10.75 10.25h2.5V9.5q0-1.25-1.25-1.25T10.75 9.5zm4 .497V9.5q0-2.75-2.75-2.75T9.25 9.5v1.088q-1 .581-1 2.162v1.5q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768q-.129-.129-.268-.235");
}

</style>
