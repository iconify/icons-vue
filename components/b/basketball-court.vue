<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpzs_ybyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-court" /></template>
<style>
.gpzs_ybyt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.625 1.75h10.75q3.375 0 3.375 3.375v3.75q0 2.788-2.303 3.273q.303.375.303.852q0 .723-.697 1.214l-2.341 7.023q-.019.056-.046.108t-.062.099t-.076.089t-.089.075q-.048.035-.1.061q-.053.027-.109.045q-.055.018-.113.027T15 21.75H9q-.059 0-.117-.009t-.113-.027q-.056-.018-.109-.045q-.052-.026-.1-.061q-.047-.034-.089-.075t-.076-.089t-.062-.099t-.046-.108l-2.341-7.023Q5.25 13.723 5.25 13q0-.477.303-.852q-2.303-.485-2.303-3.273v-3.75q0-3.375 3.375-3.375m6.125 18.5h1.709l1.781-5.343q-1.37.293-3.49.336zm-1.5-5.007q-2.12-.043-3.49-.336l1.781 5.343h1.709zM10.5 4.75Q8.25 4.75 8.25 7v.5q0 2.25 2.25 2.25h3q2.25 0 2.25-2.25V7q0-2.25-2.25-2.25z");
}

</style>
