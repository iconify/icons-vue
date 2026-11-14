<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipqwc3r3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:electronics-store" /></template>
<style>
.ipqwc3r3l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.311 6.205l19.439.274v.022q-.002 2.997-3 2.997q-1.499 0-2.249-.749q-.75.751-2.251.751T12 8.75q-.75.75-2.25.75t-2.251-.751q-.75.75-2.249.75q-2.999 0-3-2.999q0-.154.061-.295m4.916 6.022q-1.238 1.238-1.701 2.798Q3.5 15.249 3.5 17.5v2.25q0 1.036.732 1.768T6 22.25h.25q1.036 0 1.768-.732t.732-1.768V17.5q0-2.035-1.656-2.413q.383-.988 1.194-1.799Q9.825 11.75 12 11.75t3.712 1.538q.811.811 1.194 1.799q-1.656.378-1.656 2.413v2.25q0 1.036.732 1.768t1.768.732H18q1.036 0 1.768-.732t.732-1.768V17.5q0-1.036-.732-1.768q-.557-.556-1.289-.69q-.461-1.57-1.706-2.815Q14.796 10.25 12 10.25t-4.773 1.977");
}

</style>
