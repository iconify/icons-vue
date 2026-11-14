<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfl3qw2sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-palette-strip" /></template>
<style>
.yfl3qw2sa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 5.25h1q2.5 0 2.5 2.5v8.5q0 1.036-.732 1.768t-1.768.732h-1q-1.036 0-1.768-.732T1.75 16.25v-8.5q0-2.5 2.5-2.5m7.25 0h1q1.036 0 1.768.732T15 7.75v8.5q0 1.036-.732 1.768t-1.768.732h-1q-1.036 0-1.768-.732T9 16.25v-8.5q0-2.5 2.5-2.5m8.25 0h-1q-2.5 0-2.5 2.5v8.5q0 1.036.732 1.768t1.768.732h1q1.036 0 1.768-.732t.732-1.768v-8.5q0-1.036-.732-1.768T19.75 5.25");
}

</style>
