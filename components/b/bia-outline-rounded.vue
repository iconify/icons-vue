<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1qbfjmjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bia-outline-rounded" /></template>
<style>
.r1qbfjmjk {
  fill: currentColor;
  d: path("M6.5 18v-2q0-.213.143-.357T7 15.5t.357.143T7.5 16v2h3v-2q0-.213.143-.357T11 15.5t.357.143t.143.357v2h3v-2q0-.213.143-.357T15 15.5t.357.143t.143.357v2h3.885q.269 0 .442-.173t.173-.442V9.96q-.729.61-1.863.882q-1.133.274-2.349.274q-.875 0-1.738-.145t-1.579-.471H4.616q-.27 0-.443.173T4 11.116v6.269q0 .269.173.442t.443.173zM7 9.5h4.17q-.287-.302-.44-.667T10.577 8q0-.275.047-.525t.16-.475H7.617q-.27 0-.443.173T7 7.616zm11.658.212Q20 9.308 20 8t-1.342-1.711t-2.87-.404t-2.869.404Q11.577 6.692 11.577 8t1.342 1.712t2.87.404t2.869-.404M4.616 19q-.672 0-1.144-.472T3 17.385v-6.27q0-.67.472-1.143q.472-.472 1.144-.472H6V7.616q0-.672.472-1.144T7.616 6h3.99q.754-.596 1.877-.856t2.306-.26q1.928 0 3.57.719Q21 6.321 21 8v9.385q0 .67-.472 1.143q-.472.472-1.143.472zM6.5 18H20H4z");
}

</style>
