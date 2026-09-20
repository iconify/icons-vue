<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krqha_a5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-column-right-rounded" /></template>
<style>
.krqha_a5j {
  fill: currentColor;
  d: path("M18.143 14.356Q18 14.213 18 14v-1.5h-1.5q-.213 0-.356-.144T16 11.999t.144-.356t.356-.143H18V10q0-.213.144-.356t.357-.144t.356.144T19 10v1.5h1.5q.213 0 .356.144t.144.357t-.144.356t-.356.143H19V14q0 .213-.144.356t-.357.144t-.356-.144M4.616 20q-.667 0-1.141-.475T3 18.386V5.615q0-.666.475-1.14T4.615 4h5.943v16zm6.942 0V4h5.827q.666 0 1.14.475T19 5.615v1.043q0 .2-.146.332q-.146.131-.354.126q-2.027 0-3.456 1.42Q13.615 9.959 13.615 12t1.43 3.464q1.428 1.42 3.455 1.42q.2 0 .35.128t.15.33v1.043q0 .666-.475 1.14t-1.14.475z");
}

</style>
