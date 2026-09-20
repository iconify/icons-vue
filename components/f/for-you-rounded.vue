<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlczzza5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:for-you-rounded" /></template>
<style>
.vlczzza5v {
  fill: currentColor;
  d: path("M15.375 11.738q1.75-.263 3.25-.738q.5-.2.938.125t.437.85v7.15q0 .625-.363 1.138T18.7 21q-1.425.475-3.187.738T12 22t-3.512-.262T5.3 21q-.575-.225-.937-.737T4 19.124v-7.15q0-.525.438-.85T5.375 11q1.5.475 3.25.738T12 12t3.375-.262m-.55-8.563Q16 4.35 16 6t-1.175 2.825T12 10T9.175 8.825T8 6t1.175-2.825T12 2t2.825 1.175");
}

</style>
