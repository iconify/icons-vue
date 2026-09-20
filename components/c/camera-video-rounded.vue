<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm0up5bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-video-rounded" /></template>
<style>
.zm0up5bvp {
  fill: currentColor;
  d: path("M10.232 11.765Q9.5 11.029 9.5 9.996t.736-1.764t1.768-.732t1.764.736t.732 1.768t-.735 1.764t-1.769.732t-1.764-.735M6.499 8.73q.31 0 .521-.21q.21-.21.21-.52t-.21-.521q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21M5 20q-.213 0-.356-.144t-.144-.357t.144-.356T5 19h2.648l.756-3.042q-2.283-.214-3.843-1.911T3 10q0-2.507 1.747-4.253Q6.493 4 9 4h6q2.507 0 4.254 1.747Q21 7.493 21 10q0 2.35-1.56 4.047t-3.844 1.91L16.352 19H19q.213 0 .356.144t.144.357t-.144.356T19 20zm9.479-7.521Q15.5 11.458 15.5 10t-1.021-2.479T12 6.5T9.521 7.521T8.5 10t1.021 2.479T12 13.5t2.479-1.021");
}

</style>
