<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aodrjq6fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:email-security" /></template>
<style>
.aodrjq6fq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 3.75H6q-1.76 0-3.005 1.245q-.636.636-.947 1.407q.128-.097.285-.133q.146-.033.293-.008t.273.104l8.351 5.249l8.351-5.249q.126-.079.273-.104t.293.008q.157.036.285.133q-.311-.771-.947-1.407Q18.26 3.75 16.5 3.75m4.195 3.532q-.091.224-.296.353l-8.75 5.5q-.09.056-.191.086t-.208.029q-.106 0-.208-.029t-.191-.086l-8.75-5.5q-.205-.129-.296-.353Q1.75 7.63 1.75 8v7q0 1.76 1.245 3.005T6 19.25h7q0-2.387 1.52-3.255Q14.762 13 18 13q1.88 0 2.75 1.01V8q0-.37-.055-.718m.323 10.2q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
