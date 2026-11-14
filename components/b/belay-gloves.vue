<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzvomgkeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:belay-gloves" /></template>
<style>
.rzvomgkeq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 15.863v-2.052L4.22 10.78q-.014-.013-.026-.027q-1.608-1.777.087-3.472q1.454-1.454 2.969-.477V6.5q0-1.76 1.245-3.005T11.5 2.25t3.005 1.245T15.75 6.5v9.363q2 .799 2 2.637q0 .691-.283 1.236l2.347 1.083q.067.031.127.074q.06.044.11.098t.089.117t.064.133t.037.142t.008.147t-.02.145q-.017.072-.048.139t-.074.127t-.098.11t-.117.089t-.133.064q-.069.025-.142.037t-.147.008q-.074-.003-.145-.02q-.072-.017-.139-.048l-2.859-1.319q-1.559.888-4.827.888q-6.25 0-6.25-3.25q0-1.838 2-2.637m7-.407V6.5q0-1.139-.805-1.945q-.806-.805-1.945-.805q-2.75 0-2.75 2.75v2q0 .149-.057.287t-.163.243q-.105.106-.243.163T8 9.25t-.287-.057t-.243-.163l-.736-.735q-.713-.633-1.392.047q-.68.679-.047 1.392L8.53 12.97q.106.105.163.243t.057.287v1.956q1.177-.206 2.75-.206t2.75.206");
}

</style>
