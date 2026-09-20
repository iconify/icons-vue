<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsjftd3ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:digital-wellbeing-rounded" /></template>
<style>
.xsjftd3ly {
  fill: currentColor;
  d: path("M9.525 7.975Q8.5 6.95 8.5 5.5t1.025-2.475T12 2t2.475 1.025T15.5 5.5t-1.025 2.475T12 9T9.525 7.975m1.05 12.6L6 16q-.5-.5-.75-1.125T5 13.5q0-1.475 1.013-2.488T8.5 10q.725 0 1.338.275t1.112.775L12 12.1l1.05-1.05q.5-.5 1.113-.775T15.5 10q1.475 0 2.488 1.013T19 13.5q0 .75-.25 1.375T18 16l-4.575 4.575q-.3.3-.675.45t-.75.15t-.75-.15t-.675-.45");
}

</style>
