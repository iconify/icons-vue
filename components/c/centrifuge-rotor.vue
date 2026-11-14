<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoresrbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:centrifuge-rotor" /></template>
<style>
.xoresrbcc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M12 4.5Q9.5 4.5 9.5 7T12 9.5q1.036 0 1.768-.732T14.5 7t-.732-1.768T12 4.5m-6.768 9.268q.732.733 1.768.733t1.768-.733T9.5 12q.001-1.036-.732-1.768Q8.036 9.499 7 9.499t-1.768.733T4.5 12t.732 1.768M14.5 12q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5M12 14.5q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T14.5 17t-.732-1.768T12 14.5");
}

</style>
