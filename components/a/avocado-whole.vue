<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_d--f9_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:avocado-whole" /></template>
<style>
.q_d--f9_v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.272 3.51q2.213.932 3.924 5.211q.331.827 1.252 2.283Q20.25 13.852 20.25 16q0 2.658-2.503 4.494Q15.352 22.25 12 22.25t-5.747-1.756Q3.75 18.658 3.75 16q0-2.148 1.802-4.996q.921-1.456 1.252-2.283q2.04-5.1 4.792-5.446l1.044-1.461q.086-.121.213-.2t.274-.104q.147-.024.292.009q.146.034.267.121q.06.043.111.096q.05.054.089.117t.066.132q.026.069.038.142t.01.146t-.019.146t-.047.139q-.031.068-.074.128zM8.25 15.5q0 3.75 3.75 3.75t3.75-3.75T12 11.75T8.25 15.5");
}

</style>
