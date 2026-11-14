<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyucpcbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:courier-handheld" /></template>
<style>
.eyucpcbtx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 2.25h16q1.346 0 2.298.952T21.75 5.5v4q0 1.346-.952 2.298t-2.298.952h-1.585l1.311 6.554q.368 1.106-.339 2.049q-.718.956-1.907.897H13.5q-1.918.027-2.24-1.875L9.949 13.16l-.728 2.546q-.041.143-.134.26q-.092.117-.223.19q-.13.072-.278.089t-.292-.024q-.071-.02-.137-.054q-.065-.034-.123-.08t-.106-.102t-.084-.121t-.058-.135t-.031-.143t-.002-.147t.026-.145l.881-3.083l-6.384-1.995q-.057-.018-.11-.044q-.053-.027-.102-.062q-.048-.034-.091-.076t-.077-.09q-.036-.048-.063-.101t-.046-.109q-.018-.057-.028-.116Q1.75 9.56 1.75 9.5V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m14 3H14q-2.25 0-2.25 2.25T14 9.75h2.5q2.25 0 2.25-2.25T16.5 5.25");
}

</style>
