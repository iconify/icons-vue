<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5w4k11jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cloud-alert-outline" /></template>
<style>
.v5w4k11jg {
  fill: currentColor;
  d: path("M6.5 19q-1.871 0-3.185-1.301Q2 16.397 2 14.516q0-1.71 1.175-3.047t2.921-1.435q.337-2.185 2.01-3.61T12 5q2.507 0 4.254 1.747Q18 8.493 18 11v1h.616q1.436.046 2.41 1.055T22 15.5q0 1.471-1.014 2.486Q19.97 19 18.5 19zm0-1h12q1.05 0 1.775-.725T21 15.5t-.725-1.775T18.5 13H17v-2q0-2.075-1.463-3.538T12 6T8.463 7.463T7 11h-.5q-1.45 0-2.475 1.025T3 14.5t1.025 2.475T6.5 18m5.857-3.163q.143-.144.143-.357t-.144-.356t-.357-.143t-.356.144t-.143.357t.144.356t.357.143t.356-.144M11.5 12.48h1V8.5h-1z");
}

</style>
