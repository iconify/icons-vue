<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5hdr6g7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:activity-log-home" /></template>
<style>
.d5hdr6g7n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143Q2.75 10.154 2.75 11.711v6.164q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-6.164q0-1.557-1.185-2.568L14.19 4.132q-2.19-1.866-4.38 0zM9.25 9.5h5.5q2.5 0 2.5 2.5v4.5q0 2.5-2.5 2.5h-5.5q-2.5 0-2.5-2.5V12q0-2.5 2.5-2.5");
}

</style>
