<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3u2rxa3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:joggers" /></template>
<style>
.l3u2rxa3q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 1.75h-11Q4.25 1.75 4.25 4q0 1.515 1.02 2.01l.481 12.02q.005.137.058.263t.148.225q-.207.512-.207 1.232q0 1.036.732 1.768t1.768.732t1.768-.732t.732-1.768q0-.72-.207-1.232q.144-.151.189-.355L12 12.457l1.268 5.706q.045.204.189.355q-.207.512-.207 1.232q0 1.036.732 1.768t1.768.732t1.768-.732t.732-1.768q0-.72-.207-1.232q.094-.099.148-.225t.058-.263l.481-12.02q1.02-.495 1.02-2.01q0-2.25-2.25-2.25m-1.75 15.5h-1.148l-1.87-8.413q-.023-.104-.075-.198q-.051-.094-.127-.169q-.075-.076-.169-.127t-.198-.075q-.072-.016-.146-.018t-.147.011t-.141.04t-.132.066q-.062.04-.115.091t-.096.112t-.072.128t-.046.139l-1.87 8.413H7.221l-.44-11h10.438l-.44 11z");
}

</style>
