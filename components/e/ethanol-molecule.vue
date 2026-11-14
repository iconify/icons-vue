<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1p5d3bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ethanol-molecule" /></template>
<style>
.o1p5d3bql {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 5.75Q7.25 5.75 7.25 9q0 1.16.414 1.907l-.934 1.168Q6.027 11.75 5 11.75q-3.25 0-3.25 3.25T5 18.25T8.25 15q0-1.16-.414-1.907l.934-1.168q.703.325 1.73.325q.816 0 1.488-.35l.774 1.032q-.512.778-.512 2.068q0 3.25 3.25 3.25T18.75 15q0-1.388-.593-2.183l.604-.691q.433.124.989.124q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732q-2.5 0-2.5 2.5q0 .89.317 1.463l-.647.739q-.609-.202-1.42-.202q-.907 0-1.56.253l-.813-1.083q.623-.831.623-1.92q0-1.346-.952-2.298T10.5 5.75");
}

</style>
