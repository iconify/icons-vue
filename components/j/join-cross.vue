<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul2vz_4oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:join-cross" /></template>
<style>
.ul2vz_4oe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 2q-2.5 0-2.5 2.5T3.75 7q1.01 0 1.732-.697L10.96 12l-5.478 5.697Q4.76 17 3.75 17q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732q.451-.452.624-1.018h11.675Q18.158 22 20.25 22q1.036 0 1.768-.732t.732-1.768t-.732-1.768T20.25 17q-1.212 0-1.837.588L13.04 12l5.373-5.588Q19.038 7 20.25 7q1.036 0 1.768-.732T22.75 4.5t-.732-1.768T20.25 2q-2.092 0-2.433 1.75H6.142q-.173-.566-.624-1.018Q4.786 2 3.75 2m13.7 3.25L12 10.918L6.55 5.25zm-10.9 13.5L12 13.082l5.45 5.668z");
}

</style>
