<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m30lo0bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:house-water" /></template>
<style>
.m30lo0bvf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v3.613q-.717-1.02-1.776-2.175q-.133-.146-.292-.262t-.337-.2q-.179-.083-.37-.13t-.388-.055t-.392.021t-.379.098q-.185.067-.354.169t-.313.236q-.065.058-.123.123Q13.25 16.722 13.25 19q0 1.239.552 2.25H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m13.512 4.85q.022-.024.046-.046q.055-.05.118-.088t.132-.064q.07-.025.143-.036q.073-.012.147-.008q.073.003.145.02t.139.049t.126.075t.11.098Q21.5 17.208 21.5 19q0 1.45-1.025 2.475T18 22.5q-3.5 0-3.5-3.5q0-1.792 2.947-5.007M16 19q0-1.069 2-3.374q2 2.305 2 3.374q0 .828-.586 1.414T18 21q-2 0-2-2m2-1.413q-.75.994-.75 1.413q0 .75.75.75t.75-.75q0-.419-.75-1.413");
}

</style>
