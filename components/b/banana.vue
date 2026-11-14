<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi4qc7bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:banana" /></template>
<style>
.pi4qc7bte {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.267 4.843q.023-.107.075-.204q.053-.096.131-.173t.175-.128t.205-.073l2.5-.5q.071-.015.143-.015q.073 0 .144.013q.071.014.139.041q.067.027.128.066t.113.089t.094.11t.071.126t.046.136q2.453 10.631 10.883 11.928q.063.009.123.029q.826.276 1.183.948q.354.667.102 1.406q-.514 1.509-2.485 1.607q-7.475.374-11.442-4.726q-3.62-4.654-2.328-10.68");
}

</style>
