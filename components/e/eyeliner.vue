<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b867qlb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyeliner" /></template>
<style>
.b867qlb5t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.743 6.568q.215.443.215.975q0 .932-.66 1.592l-1.414 1.413q-.659.66-1.591.66t-1.592-.66t-.659-1.591q0-.932.66-1.591l1.414-1.414q.659-.66 1.591-.66q.532 0 .975.215L19.42 2.77q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243zM7 8.75h1.5q2.25 0 2.25 2.25q0 .414-.13.775q.8.109 1.398.707q.732.732.732 1.768v5.5q0 1.036-.732 1.768t-1.768.732h-5q-1.036 0-1.768-.732T2.75 19.75v-5.5q0-2.306 2.127-2.485q-.127-.356-.127-.765q0-2.25 2.25-2.25");
}

</style>
