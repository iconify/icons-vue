<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8h-toyzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:backup-offsite" /></template>
<style>
.m8h-toyzu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 16.75q-1.864 0-3.182-1.318T2 12.25t1.318-3.182q1.084-1.084 2.537-1.276q.817-4.157 5.217-4.786q4.477-.64 6.415 3.264q1.863.155 3.225 1.518Q22.25 9.325 22.25 11.5q0 1.589-.821 2.838l-.689-.575q-2.24-1.865-4.48.001l-1.5 1.249q-.873.727-1.141 1.737zM14.75 20v-2.297q0-1.054.81-1.729l1.5-1.25q1.44-1.2 2.88 0l1.5 1.25q.81.675.81 1.729V20q0 2.25-2.25 2.25h-3q-2.25 0-2.25-2.25m1.5 0q0 .75.75.75h3q.75 0 .75-.75v-2.297q0-.352-.27-.577l-1.5-1.25q-.48-.4-.96 0l-1.5 1.25q-.27.225-.27.577z");
}

</style>
