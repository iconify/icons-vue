<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjm_7s7hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-repair-rounded" /></template>
<style>
.vjm_7s7hi {
  fill: currentColor;
  d: path("M11.643 20.626q-.143-.143-.143-.357v-2.5H5q-.213 0-.357-.143t-.143-.357t.143-.356t.357-.144h14q.214 0 .357.144t.143.356t-.143.357t-.357.143h-6.5v2.5q0 .214-.143.357t-.357.143t-.357-.143m-2.488-8.817q.23-.23.23-.54t-.23-.54t-.54-.229t-.539.23t-.23.54q0 .309.23.539t.54.23t.539-.23m6.769 0q.23-.23.23-.54t-.23-.54t-.54-.229t-.539.23t-.23.54t.23.539t.54.23t.539-.23m-9.78 3.817Q6 15.483 6 15.269V9.791q0-.137.016-.27q.015-.135.065-.265L7.277 5.85q.162-.485.571-.783q.41-.298.944-.298h6.416q.534 0 .944.298t.571.783l1.196 3.406q.05.13.066.264q.015.134.015.27v5.48q0 .213-.143.356t-.357.143t-.357-.143t-.143-.357v-1.5H7v1.5q0 .214-.143.357t-.357.143t-.357-.143m1.16-6.857h9.393l-.912-2.596q-.057-.192-.211-.298t-.365-.106H8.792q-.211 0-.365.106t-.211.298z");
}

</style>
