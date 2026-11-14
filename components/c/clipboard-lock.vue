<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihd_0iwqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:clipboard-lock" /></template>
<style>
.ihd_0iwqr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.757 4.25H6.5Q3.75 4.25 3.75 7v12q0 2.75 2.75 2.75h11q2.75 0 2.75-2.75V7q0-2.75-2.75-2.75h-1.262q-.078-.772-.647-1.341Q14.932 2.25 14 2.25h-.75q1.243 0 2.121.879q.879.878.879 2.121q0 3-3 3h-2.5q-3 0-3-3q0-1.243.879-2.121q.878-.879 2.121-.879H10q-2.121 0-2.243 2m1.932-.061q.44-.439 1.061-.439h2.5q.621 0 1.061.439q.439.44.439 1.061q0 1.5-1.5 1.5h-2.5q-1.5 0-1.5-1.5q0-.621.439-1.061m1.561 9.061v-.5q0-.75.75-.75t.75.75v.5zm3 .497q.139.106.268.235q.732.732.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-1.5q-1.036 0-1.768-.732T8.75 16.25v-.5q0-1.581 1-2.162v-.838q0-2.25 2.25-2.25t2.25 2.25z");
}

</style>
