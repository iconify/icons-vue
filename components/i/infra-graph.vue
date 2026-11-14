<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxiplrdes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:infra-graph" /></template>
<style>
.nxiplrdes {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.995 3.745Q7.75 4.99 7.75 6.75t1.245 3.005q.126.127.258.24l-2.844 5.079Q5.992 15 5.5 15q-3.25 0-3.25 3.25T5.5 21.5q2.85 0 3.201-2.5h6.598q.351 2.5 3.201 2.5q1.346 0 2.298-.952t.952-2.298t-.952-2.298T18.5 15q-.492 0-.909.074l-2.844-5.079q.132-.113.258-.24Q16.25 8.51 16.25 6.75t-1.245-3.005T12 2.5T8.995 3.745M15.299 17.5H8.701q-.168-1.199-.911-1.823l2.756-4.92Q11.222 11 12 11t1.454-.243l2.756 4.92q-.743.624-.911 1.823");
}

</style>
