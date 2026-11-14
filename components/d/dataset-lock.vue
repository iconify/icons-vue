<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrdruxb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dataset-lock" /></template>
<style>
.lrdruxb9x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 6v12q0 3.25 3.25 3.25h7.126q-.126-.474-.126-1v-.5h-1.75V15.5h3.542q.104-.879.465-1.5H10.75V9.75h9.5v3.495q.208.16.402.353q1.032 1.033 1.094 2.468l.004.003V6q0-1.346-.952-2.298T18.5 2.75h-13q-1.346 0-2.298.952T2.25 6m7 3.75V14h-5.5V9.75zm12.268 7.732q-.452-.451-1.018-.624v-.608q0-1.036-.732-1.768T18 13.75q-2.5 0-2.5 2.5v.567q-1.75.341-1.75 2.433v1q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768M17 16.25v.5h2v-.5q0-.414-.293-.707T18 15.25q-1 0-1 1m-7.75-.75v4.25H5.5q-1.75 0-1.75-1.75v-2.5zm6.293 5.457q-.293-.293-.293-.707v-1q0-1 1-1h3.5q.414 0 .707.293t.293.707v1q0 .414-.293.707t-.707.293h-3.5q-.414 0-.707-.293M16.5 20v-.25h2q.506 0 .909-.25h.091v.5z");
}

</style>
