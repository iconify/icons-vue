<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heso5jgkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-shield-sharp" /></template>
<style>
.heso5jgkr {
  fill: currentColor;
  d: path("M2 17V7h13.227l-2.92 1q-.022 2.396.736 4.87T15.62 17zm16.5-.77q-1.654-.609-2.73-2.516T14.691 9.46q.756-.028 1.673-.432q.918-.404 2.135-1.26q1.217.856 2.135 1.26t1.673.432q0 2.345-1.077 4.252t-2.73 2.52m0-1.09q1.067-.537 1.827-1.874q.76-1.336.932-2.973q-.594-.142-1.268-.468T18.5 8.971z");
}

</style>
