<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7zqmw3qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dragonfly" /></template>
<style>
.z7zqmw3qa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.5Q9.5 2.5 9.5 5q0 2.092 1.75 2.433v.28q-.18-.08-.381-.155q-1.517-.559-3.619-.559t-3.619.559Q1.75 8.252 1.75 9.499v.002q0 1.247 1.881 1.941q1.517.559 3.619.559t3.619-.559q.201-.075.381-.155v2.255Q9.944 13 7.5 13q-5.25 0-5.25 2.5T7.5 18q2.444 0 3.75-.542V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.187q.141.064.295.124q1.45.564 3.455.564t3.455-.564q1.797-.699 1.795-1.938q.002-1.237-1.795-1.936q-1.45-.564-3.455-.564t-3.455.564q-.154.06-.295.124v-2.258q1.372.571 4 .571q5.5 0 5.5-2.5T16.75 7q-2.628 0-4 .571v-.179q.566-.173 1.018-.624Q14.5 6.036 14.5 5t-.732-1.768T12 2.5");
}

</style>
