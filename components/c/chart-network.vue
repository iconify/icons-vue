<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajjorlbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-network" /></template>
<style>
.ajjorlbnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2q3 0 3 3t-3 3q-.786 0-1.366-.206l-1.811 2.304q.677.863.677 2.402q0 1.095-.342 1.847l1.552 1.552q.695-.399 1.79-.399q3 0 3 3t-3 3t-3-3q0-.845.238-1.452l-1.565-1.565Q13.345 16 12 16t-2.173-.517l-1.565 1.565q.238.607.238 1.452q0 3-3 3t-3-3t3-3q1.095 0 1.79.399l1.552-1.552Q8.5 13.595 8.5 12.5q0-1.402.562-2.243L7.393 8.284Q6.804 8.5 6 8.5q-3 0-3-3t3-3t3 3q0 1.141-.434 1.848l1.66 1.962Q10.958 9 12 9q.915 0 1.59.239l1.86-2.366Q15 6.161 15 5q0-3 3-3");
}

</style>
