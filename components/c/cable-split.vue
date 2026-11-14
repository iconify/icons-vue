<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia2zc6b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cable-split" /></template>
<style>
.ia2zc6b2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 1.75h.5q1.036 0 1.768.732T8.25 4.25v1q0 1.036-.732 1.768q-.549.548-1.268.686V8q0 .944 2.604 2.042q2.187.922 3.146 2.056q.959-1.134 3.146-2.056Q17.75 8.944 17.75 8v-.278q-2-.236-2-2.472v-1q0-2.5 2.5-2.5h.5q2.5 0 2.5 2.5v1q0 2.236-2 2.472V8q0 1.94-3.521 3.424Q12.75 12.68 12.75 14v1.778q2 .236 2 2.472v1.5q0 1.036-.732 1.768t-1.768.732h-.5q-1.036 0-1.768-.732T9.25 19.75v-1.5q0-2.236 2-2.472V14q0-1.32-2.979-2.576Q4.75 9.94 4.75 8v-.278q-2-.236-2-2.472v-1q0-1.036.732-1.768T5.25 1.75");
}

</style>
