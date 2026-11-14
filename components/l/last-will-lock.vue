<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtnuct9gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:last-will-lock" /></template>
<style>
.jtnuct9gz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 1.75H6q-1.139 0-1.945.805q-.805.806-.805 1.945q0 2.345 2 2.69v9.657q-.668.182-1.195.708q-.805.806-.805 1.945q0 2.75 2.75 2.75h7.954Q13 21.198 13 19.75v-.5q0-1.585.67-2.5H6.75v-9.5h10.5v5.795Q17.602 13 18 13t.75.045V7.19q2-.345 2-2.69q0-2.75-2.75-2.75m3.018 15.732q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
