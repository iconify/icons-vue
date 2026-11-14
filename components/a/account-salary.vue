<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5zv1nbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:account-salary" /></template>
<style>
.c5zv1nbwh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 10V5.5q0-1.75 1.75-1.75h14q1.75 0 1.75 1.75V10q0 .116-.035.227q.148.126.29.268q.361.361.617.765q-.121-.02-.242 0q-.121.019-.229.076L12 16.152l-9.151-4.816q-.108-.057-.229-.076q-.121-.02-.242 0q.256-.404.617-.765q.142-.142.29-.268q-.035-.111-.035-.227m-1.371 2.42q-.129.514-.129 1.08V18q0 1.76 1.245 3.005T6 22.25h12q1.76 0 3.005-1.245T22.25 18v-4.5q0-.566-.129-1.08q-.105.156-.272.244l-9.5 5q-.08.042-.169.064t-.18.022t-.18-.022t-.169-.064l-9.5-5q-.167-.088-.272-.244M19.25 5.5q0-.25-.25-.25h-7q3 0 3 2t-3 2h6q.661 0 1.25.176zM5 5.25q-.25 0-.25.25v3.926Q5.339 9.25 6 9.25h6q-3 0-3-2t3-2z");
}

</style>
