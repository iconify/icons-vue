<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_1_30bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloud-recording" /></template>
<style>
.d_1_30bqb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 18.25h-.022q-4.233-.122-4.506-4.349q-.256-3.969 3.417-4.797q1.192-4.27 5.78-4.583q4.602-.314 6.359 3.78q1.751.257 2.965 1.622q1.377 1.551 1.256 3.621q-.016.271-.057.529q-.061-.038-.125-.074q-1.118-.634-2.223-.257Q18.918 13 17.25 13h-1.5Q12 13 12 16.75v1.5zm10.25-4h-1.5q-2.5 0-2.5 2.5v1.5q0 2.5 2.5 2.5h1.5q1.656 0 2.215-1.096l.399.239q.787.473 1.587.02t.799-1.371v-2.083q.001-.919-.799-1.372t-1.587.02l-.399.239q-.559-1.096-2.215-1.096m1 2.5v1.5q0 1-1 1h-1.5q-1 0-1-1v-1.5q0-1 1-1h1.5q1 0 1 1m1.864 1.544q-.364-.219-.364-.643v-.302q0-.424.364-.643l.522-.313q.038-.023.076-.001t.038.065v2.085q0 .045-.038.066t-.076-.001zM17 18v-1h-1v1z");
}

</style>
