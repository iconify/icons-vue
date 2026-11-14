<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjwh7_bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:api-lock" /></template>
<style>
.zjwh7_bht {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.869 5.597h.001q.18.103.283.283v.001q.097.172.097.369v6.755Q18.127 13 18 13q-3.238 0-3.48 2.995q-1.122.64-1.416 2.108l-2.734 1.55q-.172.097-.37.097t-.37-.097l-7.5-4.25q-.086-.05-.157-.119q-.071-.07-.121-.156t-.076-.182t-.026-.196v-8.5q0-.198.097-.37l.005-.008q.102-.175.278-.275h.001l7.499-4.25q.085-.047.179-.072T10 1.25t.191.025t.179.072zm3.149 11.885q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
