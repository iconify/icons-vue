<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzilzsjuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-mode" /></template>
<style>
.pzilzsjuz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v1.65q-.241-.405-.598-.763Q19.553 11.5 18 11.5q-3.75 0-3.75 3.75q0 1.275.433 2.116Q12.5 18.415 12.5 21.25H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568M15.5 15.25q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1m1-.25q.25 0 .25.25t-.25.25t-.25-.25T18 15m3.154 2.292q.05-.076.096-.153v.195zM18 18q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3q-.189-1.5-2.735-1.5T15.265 21z");
}

</style>
