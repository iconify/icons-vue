<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0i540-kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:degrees-celsius" /></template>
<style>
.i0i540-kj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.25q-3.25 0-3.25 3.25T6 9.75T9.25 6.5T6 3.25m8.578 16.988q2.876.167 5.082-1.684q.057-.048.103-.106t.08-.123t.055-.136t.027-.145q.007-.073-.001-.147q-.009-.073-.031-.144t-.057-.135t-.084-.121q-.047-.057-.105-.103t-.123-.08t-.136-.055t-.145-.027q-.073-.007-.147.001q-.073.009-.144.031t-.135.057t-.121.083q-1.75 1.469-4.031 1.336q-2.28-.132-3.848-1.794Q9.25 15.284 9.25 13t1.567-3.946t3.848-1.794t4.031 1.335q.114.096.256.141t.291.032t.281-.082t.228-.183q.048-.056.084-.121q.035-.065.057-.135t.031-.144t.001-.147q-.006-.074-.027-.145t-.055-.136t-.08-.123t-.103-.105q-2.206-1.852-5.082-1.685T9.726 8.025Q7.75 10.12 7.75 13t1.976 4.975t4.852 2.263");
}

</style>
