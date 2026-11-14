<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0l6ovbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:critical-path" /></template>
<style>
.k0l6ovbbq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 5.5Q9.5 3 12 3q1.036 0 1.768.732T14.5 5.5q0 .493-.166.918l4.174 3.415Q19.088 9.5 20 9.5q2.5 0 2.5 2.5T20 14.5q-.4 0-.736-.064l-1.525 2.204q.511.674.511 1.86q0 2.75-2.75 2.75q-2.345 0-2.69-2h-1.62q-.345 2-2.69 2q-2.75 0-2.75-2.75q0-1.186.511-1.86l-1.525-2.204Q4.4 14.5 4 14.5q-2.5 0-2.5-2.5T4 9.5q.912 0 1.492.333l4.123-3.374Q9.5 6.037 9.5 5.5m6.959 10.352l1.501-2.167q-.46-.613-.46-1.685q0-.537.115-.959L13.39 7.583Q12.781 8 12 8q-.912 0-1.492-.333l-4.123 3.374q.115.422.115.959q0 1.072-.46 1.685l1.501 2.167q.428-.102.959-.102q2.345 0 2.69 2h1.62q.345-2 2.69-2q.531 0 .959.102");
}

</style>
