<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgai91fcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:battery-tester" /></template>
<style>
.sgai91fcc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 4.75h.5q1.75 0 1.75 1.75q0 .27-.042.499q1.792.667 1.792 3.126v7.75q0 3.375-3.375 3.375h-.75q-3.375 0-3.375-3.375v-7.75q0-1.398.989-2.386q.383-.384.829-.619Q3.5 6.844 3.5 6.5q0-1.75 1.75-1.75m7.184 4.184Q10.75 10.618 10.75 13t1.684 4.066T16.5 18.75t4.066-1.684T22.25 13t-1.684-4.066T16.5 7.25t-4.066 1.684m4.912 1.448q.037-.064.085-.12t.106-.102q.058-.045.124-.079q.066-.033.137-.053t.145-.026t.147.003t.143.032t.135.059q.13.073.222.191q.092.117.132.261q.04.143.023.292q-.018.148-.091.278l-2.25 4q-.073.13-.191.222q-.117.092-.261.132q-.143.04-.292.023q-.148-.018-.278-.091q-.064-.037-.12-.085t-.102-.106q-.045-.058-.079-.124q-.033-.066-.053-.137t-.026-.145t.003-.147t.032-.143t.059-.135z");
}

</style>
