<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa95ji7ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:esim-lock" /></template>
<style>
.sa95ji7ya {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.555 2.555Q2.75 3.361 2.75 4.5v15q0 2.75 2.75 2.75h8.454Q13 21.198 13 19.75v-.5q0-2.387 1.52-3.255q.212-2.627 2.73-2.95V7q0-.149-.057-.287t-.163-.243l-4.5-4.5q-.105-.106-.243-.163T12 1.75H5.5q-1.139 0-1.945.805M8.25 6.25h2q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-2q-2.5 0-2.5-2.5v-2.5q0-2.5 2.5-2.5m12.768 11.232q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
