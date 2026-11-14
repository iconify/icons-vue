<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwxmqgayr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:issue-duplicate" /></template>
<style>
.bwxmqgayr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 8.5q0-2.796 1.977-4.773T8.5 1.75t4.773 1.977q1.616 1.616 1.911 3.778q-2.741.095-4.799 1.838q.115-.364.115-.843q0-2-2-2t-2 2t2 2q.479 0 .843-.115q-1.743 2.058-1.838 4.799q-2.162-.295-3.778-1.911Q1.75 11.296 1.75 8.5m7 7q0-2.796 1.977-4.773T15.5 8.75t4.773 1.977T22.25 15.5t-1.977 4.773T15.5 22.25t-4.773-1.977T8.75 15.5m1.5 0q0 2.175 1.538 3.712q1.537 1.538 3.712 1.538t3.712-1.538q1.538-1.537 1.538-3.712t-1.538-3.712Q17.675 10.25 15.5 10.25t-3.712 1.538Q10.25 13.325 10.25 15.5m1.316-.965q.383-2.586 2.969-2.969q-.474.919-1.262 1.707t-1.707 1.262m1.934.965q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
