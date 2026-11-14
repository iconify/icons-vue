<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2j-0nbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:face-mask-sheet" /></template>
<style>
.h2j-0nbnm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.108 4.818Q3.75 7.805 3.75 12t2.358 7.182Q8.53 22.25 12 22.25t5.892-3.068Q20.25 16.195 20.25 12t-2.358-7.182Q15.47 1.75 12 1.75T6.108 4.818M6.5 10q0-2.25 2.5-2.25q1.002 0 1.726.62q.774.664.774 1.63t-.774 1.63q-.724.62-1.726.62q-2.5 0-2.5-2.25M15 7.75q1.002 0 1.726.62q.774.664.774 1.63t-.774 1.63q-.724.62-1.726.62q-2.5 0-2.5-2.25T15 7.75m-4.25 7h2.5q2 0 2 2t-2 2h-2.5q-2 0-2-2t2-2");
}

</style>
