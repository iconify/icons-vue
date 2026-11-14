<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmg45-b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-fire-damage" /></template>
<style>
.pmg45-b4x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143Q2.75 10.154 2.75 11.711v6.164q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-6.164q0-1.557-1.185-2.568L14.19 4.132q-2.19-1.866-4.38 0zM12 20.75q-3.25 0-3.25-3.25q0-1.06 1.02-2.31q.655-.803.74-1.313q.012-.073.038-.142q.027-.069.066-.132t.089-.117q.051-.053.111-.096t.128-.074q.067-.03.139-.047q.072-.016.146-.019q.073-.002.146.01q.159.027.293.116q.744.496 1.073 1.254q.011-.063.011-.13q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.087 0 .172.02t.163.059q.079.039.146.095t.119.126q1.15 1.533 1.15 3.45q0 3.25-3.25 3.25");
}

</style>
