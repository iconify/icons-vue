<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4wp6gbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drone-pilot" /></template>
<style>
.y4wp6gbrd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 3.25h5.5q2.485 0 4.243 1.757Q19.25 6.765 19.25 9.25q0 2.17-1.34 3.785q-.812-.785-2.41-.785q-3.122 0-3.245 3H7.75q-2.485 0-4.243-1.757Q1.75 11.735 1.75 9.25t1.757-4.243Q5.265 3.25 7.75 3.25m-.5 3.5q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T9.75 9.25t-.732-1.768T7.25 6.75m4 2.5q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732q-2.5 0-2.5-2.5m4.25 4.25q-2 0-2 2t2 2q.47 0 .829-.11l.735.735l-.735.735q-.359-.11-.829-.11q-2 0-2 2t2 2t2-2q0-.47-.11-.829l.735-.735l.735.735q-.11.359-.11.829q0 2 2 2t2-2t-2-2q-.47 0-.829.11l-.735-.735l.735-.735q.359.11.829.11q2 0 2-2t-2-2t-2 2q0 .47.11.829l-.735.735l-.735-.735q.11-.359.11-.829q0-2-2-2m0 2.5q-.5 0-.5-.5t.5-.5t.5.5t-.5.5m4.75-.5q0 .5.5.5t.5-.5t-.5-.5t-.5.5m-4.75 5.75q-.5 0-.5-.5t.5-.5t.5.5t-.5.5m4.75-.5q0 .5.5.5t.5-.5t-.5-.5t-.5.5");
}

</style>
