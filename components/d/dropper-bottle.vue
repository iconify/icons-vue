<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd7kg-4xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dropper-bottle" /></template>
<style>
.rd7kg-4xr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 5.25V7q-1 .5-1 2q0 .603.161 1.044q-.776.311-1.416.951Q1.75 12.24 1.75 14v4q0 1.76 1.245 3.005T6 22.25h4q1.76 0 3.005-1.245T14.25 18v-4q0-1.76-1.245-3.005q-.64-.64-1.416-.951q.161-.441.161-1.044q0-1.5-1-2V5.25Q10.75 2.5 8 2.5T5.25 5.25m4 0v1.5h-2.5v-1.5Q6.75 4 8 4t1.25 1.25m10.35 7.8q.1.133.355.459Q22.25 16.45 22.25 18q0 3.25-3.25 3.25T15.75 18q0-1.55 2.295-4.491q.255-.326.355-.459q.044-.059.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034t.147-.007t.145.022t.138.051t.126.076q.086.064.15.15");
}

</style>
