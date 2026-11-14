<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_u9x-bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gantt-milestone" /></template>
<style>
.l_u9x-bbk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.091 4.281l1.377 1.378q.66.659.66 1.591t-.66 1.591l-1.378 1.378q-.659.66-1.591.66t-1.592-.66L14.53 8.841q-.66-.659-.66-1.591t.66-1.591l1.378-1.378q.659-.66 1.591-.66t1.591.66M4.75 4.25h4q3 0 3 3t-3 3h-4q-3 0-3-3q0-1.243.879-2.121q.878-.879 2.121-.879m14.5 10h-10q-3 0-3 3q0 1.243.879 2.121q.878.879 2.121.879h10q3 0 3-3t-3-3");
}

</style>
