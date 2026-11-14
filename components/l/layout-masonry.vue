<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8rzb-bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-masonry" /></template>
<style>
.p8rzb-bnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 2.25h-2.25q-1.398 0-2.386.989q-.989.988-.989 2.386v4.75q0 1.398.989 2.386q.988.989 2.386.989h2.25q3.375 0 3.375-3.375v-4.75q0-1.398-.989-2.386q-.988-.989-2.386-.989m10.625 0H16q-3.25 0-3.25 3.25T16 8.75h2.5q1.346 0 2.298-.952T21.75 5.5t-.952-2.298T18.5 2.25m-2.375 8h2.25q3.375 0 3.375 3.375v4.75q0 3.375-3.375 3.375h-2.25q-3.375 0-3.375-3.375v-4.75q0-3.375 3.375-3.375m-10.625 5H8q1.346 0 2.298.952t.952 2.298t-.952 2.298T8 21.75H5.5q-1.346 0-2.298-.952T2.25 18.5t.952-2.298T5.5 15.25");
}

</style>
