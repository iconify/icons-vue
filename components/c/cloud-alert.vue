<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owpezobnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cloud-alert" /></template>
<style>
.owpezobnp {
  fill: currentColor;
  d: path("M6.5 19q-1.871 0-3.185-1.301Q2 16.397 2 14.516q0-1.71 1.175-3.047t2.921-1.435q.337-2.185 2.01-3.61T12 5q2.507 0 4.254 1.747Q18 8.493 18 11v1h.616q1.436.046 2.41 1.055T22 15.5q0 1.471-1.014 2.486Q19.97 19 18.5 19zm5.857-4.163q.143-.144.143-.357t-.144-.356t-.357-.143t-.356.144t-.143.356t.144.356t.357.144t.356-.144M11.5 12.48h1V8.5h-1z");
}

</style>
