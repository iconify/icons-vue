<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e08f23w9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-hat" /></template>
<style>
.e08f23w9f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.072 12.211l1.191-6.349q.004-.025.011-.049q.548-2.126 2.737-2.063h3.978q2.189-.063 2.737 2.063q.007.024.011.049l1.191 6.349q4.322.854 4.322 3.289q0 3.75-10.25 3.75q-4.051 0-6.943-.913Q1.75 17.292 1.75 15.5q0-2.435 4.322-3.289m10.284-.242l-.135-.719H7.779l-.135.719Q9.523 11.75 12 11.75t4.356.219M15.94 9.75l-.672-3.585q-.256-.947-1.244-.915H9.976q-.988-.032-1.244.915L8.06 9.75z");
}

</style>
