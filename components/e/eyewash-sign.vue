<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmwyiq83v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyewash-sign" /></template>
<style>
.vmwyiq83v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2.25h-11q-1.76 0-3.005 1.245T2.25 6.5v11q0 1.76 1.245 3.005T6.5 21.75h11q1.76 0 3.005-1.245T21.75 17.5v-11q0-1.76-1.245-3.005T17.5 2.25M5.584 7.626q6.416-4.277 12.832 0q.061.041.114.093q.052.052.093.114q.041.061.07.129q.028.068.042.141t.015.146t-.014.147q-.015.072-.043.14t-.069.13q-.083.125-.208.208q-6.416 4.277-12.832 0q-.061-.041-.114-.093q-.052-.052-.093-.114q-.041-.061-.07-.129q-.028-.068-.042-.141t-.015-.146t.014-.147q.015-.072.043-.14t.069-.13q.083-.125.208-.208m7.026 4.938l1.218 1.705q1.674 1.751-.066 3.48q-1.762 1.749-3.524 0q-1.74-1.729-.066-3.48l1.218-1.705q.043-.06.096-.111q.054-.05.117-.089t.132-.066q.069-.026.142-.038t.146-.01t.146.019t.139.047q.068.031.128.074q.102.072.174.174");
}

</style>
