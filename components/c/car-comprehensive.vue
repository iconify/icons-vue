<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvi4ndbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-comprehensive" /></template>
<style>
.kvi4ndbxy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.75q0 1.75 1.75 1.75h.31q.345 2 2.69 2t2.69-2h3.12q.345 2 2.69 2l.102-.001l2.138-.891q.336-.443.45-1.108h.81q1.75 0 1.75-1.75V9q0-2.25-2.25-2.25h-1.155l-2.776-3.238q-.106-.125-.256-.193q-.149-.069-.313-.069h-5q-.09 0-.177.021t-.166.062t-.148.1q-.067.058-.119.131L5.614 6.75H4Q1.75 6.75 1.75 9zM15 9q-2.345 0-2.69 2H9.19Q8.845 9 6.5 9t-2.69 2H3.5q-.25 0-.25-.25V9q0-.75.75-.75h2q.09 0 .177-.021t.166-.062t.148-.1q.067-.058.119-.131L8.886 4.75h4.269l2.776 3.238q.106.125.256.193q.149.069.313.069H18q.75 0 .75.75v1.75q0 .25-.25.25h-.81Q17.345 9 15 9m3.788 5.558l3 1.25q.103.042.189.113q.085.071.147.163t.094.199t.032.217v2q0 2.709-3.455 4.189q-.141.061-.295.061t-.295-.061q-3.455-1.48-3.455-4.189v-2q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25q.138-.058.288-.058t.288.058M16.25 17v1.5q0 1.617 2.25 2.678q2.25-1.061 2.25-2.678V17l-2.25-.937z");
}

</style>
