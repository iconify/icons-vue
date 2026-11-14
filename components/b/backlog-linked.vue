<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgb5-vz0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backlog-linked" /></template>
<style>
.xgb5-vz0s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h4.5q1.76 0 3.005 1.245T14.75 6.5t-1.245 3.005T10.5 10.75H6q-1.76 0-3.005-1.245T1.75 6.5t1.245-3.005T6 2.25m13.25 0q1.243 0 2.121.879q.879.878.879 2.121v3.5q0 2.598-2.25 2.946v.608q2.25.348 2.25 2.946v3.5q0 3-3 3t-3-3v-3.5q0-2.598 2.25-2.946v-.608q-2.25-.348-2.25-2.946v-3.5q0-1.243.879-2.121q.878-.879 2.121-.879m-8.75 11H6q-1.76 0-3.005 1.245T1.75 17.5t1.245 3.005T6 21.75h4.5q1.76 0 3.005-1.245T14.75 17.5t-1.245-3.005T10.5 13.25");
}

</style>
