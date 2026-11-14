<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc-sel56h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bubble-wrap" /></template>
<style>
.gc-sel56h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 2.75H7q-1.76 0-3.005 1.245T2.75 7v10q0 1.76 1.245 3.005T7 21.25h10q1.76 0 3.005-1.245T21.25 17V7q0-1.76-1.245-3.005T17 2.75M5.5 8q0-2.5 2.5-2.5T10.5 8T8 10.5T5.5 8M16 5.5q2.5 0 2.5 2.5T16 10.5T13.5 8T16 5.5M9.5 12q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 12t-.732 1.768T12 14.5q-2.5 0-2.5-2.5m-4 4q0-2.5 2.5-2.5t2.5 2.5T8 18.5T5.5 16M16 13.5q2.5 0 2.5 2.5T16 18.5T13.5 16t2.5-2.5");
}

</style>
