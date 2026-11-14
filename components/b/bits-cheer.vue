<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc7ks7bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bits-cheer" /></template>
<style>
.kc7ks7bwv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 1.75Q2.25 1.75 2.25 5v12q0 3.25 7.75 3.25q1.475 0 2.669-.118Q12.5 19.651 12.5 19v-.339q-1.091.089-2.5.089q-6.25 0-6.25-1.75v-1.769Q5.66 16.25 10 16.25q1.377 0 2.509-.103q.049-.883.344-1.518q-1.21.121-2.853.121q-6.25 0-6.25-1.75v-1.769Q5.66 12.25 10 12.25t6.25-1.019V13h1.5V5q0-3.25-7.75-3.25m0 9q-6.25 0-6.25-1.75V7.231Q5.66 8.25 10 8.25t6.25-1.019V9q0 1.75-6.25 1.75m6 3.5h4q2.25 0 2.25 2.25V18q0 2.25-2.25 2.25h-1.474q-.263 0-.468.164l-1.309 1.047q-.604.482-1.301.148q-.696-.335-.698-1.107v-.266q-1-.118-1-1.236v-2.5q0-2.25 2.25-2.25m0 1.5q-.75 0-.75.75v2.264q.973.115.999 1.176l.871-.696q.616-.494 1.406-.494H20q.75 0 .75-.75v-1.5q0-.75-.75-.75zm1.677 1.849q.073-.284.073-.599H16.5v.838q.122.071.229.156q.448-.272.948-.395");
}

</style>
