<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upgvbdbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camcorder" /></template>
<style>
.upgvbdbko {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 2.75h-3q-1.036 0-1.768.732T3.25 5.25v1q0 1.058.448 1.668q-.37.244-.703.577Q1.75 9.74 1.75 11.5v4q0 1.76 1.245 3.005T6 19.75h6q1.76 0 3.005-1.245q.333-.333.577-.703q.61.448 1.668.448h2.5q1.036 0 1.768-.732t.732-1.768v-4.5q0-1.036-.732-1.768T19.75 8.75h-2.5q-1.058 0-1.668.448q-.244-.37-.577-.703Q13.76 7.25 12 7.25h-.877q.127-.436.127-1v-1q0-1.036-.732-1.768T8.75 2.75M6.25 13.5q0-2.75 2.75-2.75t2.75 2.75T9 16.25T6.25 13.5");
}

</style>
