<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to9nvn3lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:3g-mobiledata-rounded" /></template>
<style>
.to9nvn3lz {
  fill: currentColor;
  d: path("M4 16.5q-.213 0-.357-.143T3.5 16t.143-.357T4 15.5h3.885q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173H4q-.213 0-.357-.143T3.5 12t.143-.357T4 11.5h3.885q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442T7.885 8.5H4q-.213 0-.357-.143T3.5 8t.143-.357T4 7.5h3.885q.67 0 1.143.472q.472.472.472 1.144v1.653q0 .472-.274.822q-.274.351-.726.409q.452.058.726.409q.274.35.274.822v1.654q0 .67-.472 1.143q-.472.472-1.144.472zm10.116 0q-.672 0-1.144-.472t-.472-1.143v-5.77q0-.67.472-1.143q.472-.472 1.144-.472H20q.214 0 .357.143T20.5 8t-.143.357T20 8.5h-5.884q-.27 0-.443.173t-.173.443v5.769q0 .269.173.442t.443.173h4.769q.269 0 .442-.173t.173-.442V12.5h-2q-.213 0-.357-.143T17 12t.143-.357t.357-.143H20q.214 0 .357.143T20.5 12v2.885q0 .67-.472 1.143q-.472.472-1.143.472z");
}

</style>
