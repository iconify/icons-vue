<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz0fjmb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dag" /></template>
<style>
.kz0fjmb6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 5q0-2.75 2.75-2.75T7.75 5q0 .845-.259 1.43l3.079 3.079q.585-.259 1.43-.259q2.345 0 2.69 2h1.62q.345-2 2.69-2q2.75 0 2.75 2.75T19 14.75q-2.345 0-2.69-2h-1.62q-.345 2-2.69 2q-.845 0-1.43-.259L7.491 17.57q.259.585.259 1.43q0 2.75-2.75 2.75T2.25 19T5 16.25q.845 0 1.43.259l3.079-3.079Q9.25 12.845 9.25 12t.259-1.43L6.43 7.491Q5.845 7.75 5 7.75Q2.25 7.75 2.25 5");
}

</style>
