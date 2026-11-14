<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r__vhvb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-lock" /></template>
<style>
.r__vhvb4q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.701 8.89l4.5-3.937q2.799-2.45 5.598 0l4.5 3.937q1.451 1.27 1.451 3.198V16.5q0 1.76-1.245 3.005T16.5 20.75h-9q-1.76 0-3.005-1.245T3.25 16.5v-4.412q0-1.928 1.451-3.198m6.549 3.86h1.5v-.25q0-.75-.75-.75t-.75.75zm3 .497V12.5q0-2.25-2.25-2.25T9.75 12.5v.588q-1 .581-1 2.162v.5q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768q-.129-.129-.268-.235");
}

</style>
