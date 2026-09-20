<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndt3rbceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-wifi-4-bar-off-outline" /></template>
<style>
.ndt3rbceo {
  fill: currentColor;
  d: path("M2.094 10.177L1.012 9.133q.61-.527 1.247-.978t1.316-.845l-1.46-1.046l.848-1.218l18.17 12.731L20.285 19l-7.23-5.052q-.264-.044-.527-.063q-.262-.02-.528-.02q-1.217 0-2.351.393q-1.133.392-2.083 1.152l-1.058-1.064q.953-.794 2.08-1.264t2.349-.616l-2.443-1.724q-1.002.337-1.916.846t-1.736 1.208l-1.057-1.044q.74-.638 1.55-1.148t1.694-.877l-2.12-1.488q-.765.405-1.464.887t-1.35 1.051m8.82 8.428q-.453-.453-.453-1.086t.453-1.076T12 16t1.086.443t.452 1.076t-.453 1.086t-1.085.453t-1.086-.453m-.908-12L8.302 5.387q.925-.196 1.843-.29T12 5q3.042 0 5.87 1.045q2.828 1.046 5.118 3.088l-1.082 1.044q-2.05-1.802-4.598-2.749T12 6.481q-.5 0-.997.035q-.497.034-.997.09m9.096 6.361l-6.088-4.256q1.786.097 3.697.851q1.91.755 3.53 2.165z");
}

</style>
