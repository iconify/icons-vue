<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr2lhxbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bangles-stack" /></template>
<style>
.nr2lhxbsu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7q0-1.927 2.63-3.155Q6.727 2.75 10 2.75t5.62 1.095Q18.25 5.073 18.25 7q0 .999-.707 1.81l.077.035q2.63 1.228 2.63 3.155q0 .999-.707 1.81l.077.035q2.63 1.228 2.63 3.155t-2.63 3.155Q17.273 21.25 14 21.25t-5.62-1.095Q5.75 18.927 5.75 17q0-.999.707-1.81l-.077-.035Q3.75 13.927 3.75 12q0-.999.707-1.81l-.077-.035Q1.75 8.927 1.75 7");
}

</style>
