<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4uydccqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gpu-cluster" /></template>
<style>
.s4uydccqw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.625 2.25h1.75q1.398 0 2.386.989q.989.988.989 2.386v.125h2.5v-.125q0-1.398.989-2.386q.988-.989 2.386-.989h1.75q1.398 0 2.386.989q.989.988.989 2.386v1.75q0 3.375-3.375 3.375h-.125v2.5h.125q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375h-1.75q-3.375 0-3.375-3.375v-.125h-2.5v.125q0 3.375-3.375 3.375h-1.75q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-1.75q0-1.398.989-2.386q.988-.989 2.386-.989h.125v-2.5h-.125q-1.398 0-2.386-.989q-.989-.988-.989-2.386v-1.75q0-1.398.989-2.386q.988-.989 2.386-.989m1.625 8.5v2.5h.125q3.375 0 3.375 3.375v.125h2.5v-.125q0-3.375 3.375-3.375h.125v-2.5h-.125q-3.375 0-3.375-3.375V7.25h-2.5v.125q0 3.375-3.375 3.375z");
}

</style>
