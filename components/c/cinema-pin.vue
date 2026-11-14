<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2s3lkbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cinema-pin" /></template>
<style>
.k2s3lkbfs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 9.5q0 5.827 7.24 12.55q.051.047.111.085q.059.037.125.063q.065.026.134.039q.07.013.14.013t.14-.013t.134-.039q.066-.026.125-.063q.06-.038.111-.085q7.24-6.723 7.24-12.55q0-3.21-2.27-5.48T12 1.75T6.52 4.02T4.25 9.5m8.208-2.666l1.206.768q1.041.664 1.041 1.898t-1.041 1.898l-1.206.768q-1.124.714-2.291.073T9 10.267V8.733q0-1.331 1.167-1.972t2.29.073z");
}

</style>
