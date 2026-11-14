<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daariabiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-star" /></template>
<style>
.daariabiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339q.033-.168.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307t.169-.299t.184-.29q.095-.143.198-.281q.102-.138.211-.271t.224-.26t.237-.249q.122-.121.249-.237t.26-.224q.133-.109.271-.211q.138-.103.281-.198t.29-.184t.299-.169t.307-.155q.155-.073.314-.139t.321-.124t.326-.108t.331-.091t.335-.075t.339-.059t.341-.042t.343-.026Q11.328 3 11.5 3q.287 0 .572.023q.286.024.569.071q.282.046.56.116t.55.162t.534.206t.516.249t.493.291q.241.155.469.329t.439.368q.213.192.408.401q.196.21.374.434q.178.225.338.463q.159.238.298.489q.139.25.257.512q.118.261.215.531q.096.269.17.546M2.5 10h4v6h-4Zm14 3v-3h1.1m1.8 0h1.1v3m-2 2.5l.75 2h2l-1.5 1.5l.5 2l-1.75-1.25L16.75 21l.5-2l-1.5-1.5h2Z");
}

</style>
