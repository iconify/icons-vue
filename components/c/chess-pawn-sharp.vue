<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxum0pvnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-pawn-sharp" /></template>
<style>
.xxum0pvnx {
  fill: currentColor;
  d: path("M4 22v-5q2.2-1.5 3.225-3.125T8.625 11H6V9h2.25q-.35-.55-.55-1.175T7.5 6.5q0-1.875 1.313-3.187T12 2t3.188 1.313T16.5 6.5q0 .7-.2 1.325T15.75 9H18v2h-2.625q.375 1.25 1.4 2.875T20 17v5z");
}

</style>
