<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg0mmwbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blini" /></template>
<style>
.eg0mmwbwi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 8.25H9q-1.25 0-1.25 1.25T9 10.75h8q.187 0 .362.013q.068-.013.138-.013q1.25 0 1.25-1.25T17.5 8.25zm5.208-1.5H17.5q2.75 0 2.75 2.75q0 1.594-.924 2.264q.424.656.424 1.736q0 .74-.199 1.281q2.199.26 2.199 2.719q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75q0-1.891 1.301-2.482q-.301-.609-.301-1.518q0-2.75 2.75-2.75h.438q-.188-.531-.188-1.25q0-2.75 2.75-2.75h.292q.312-2.625 2.958-2.625t2.958 2.625m-4.382 0q.262-1.125 1.424-1.125t1.424 1.125zM17 12.25H6q-1.25 0-1.25 1.25T6 14.75h11q1.25 0 1.25-1.25T17 12.25");
}

</style>
