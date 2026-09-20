<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqoc8-b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:euro-outline-rounded" /></template>
<style>
.kqoc8-b8g {
  fill: currentColor;
  d: path("M15.039 20q-2.893 0-4.953-1.608q-2.059-1.607-2.855-4.084h-3q-.214 0-.357-.143t-.143-.357t.143-.357t.357-.143h2.8q-.114-.581-.101-1.324t.1-1.292h-2.8q-.213 0-.356-.143t-.143-.357t.143-.356t.357-.144h3.038q.777-2.476 2.827-4.084T15.038 4q1.354 0 2.57.396q1.217.396 2.265 1.12q.177.115.193.316q.015.2-.131.341q-.166.166-.38.168q-.213.003-.39-.125q-.901-.583-1.941-.9Q16.184 5 15.038 5q-2.49 0-4.232 1.353t-2.477 3.34h6.094q.214 0 .357.143t.143.356t-.143.357t-.357.143H8.056q-.12.599-.114 1.351q.006.753.114 1.265h6.367q.214 0 .357.143t.143.357t-.143.357t-.357.143H8.31q.753 1.986 2.496 3.339T15.039 19q1.145 0 2.195-.32q1.049-.318 1.931-.901q.177-.129.39-.123t.38.171q.146.14.13.341t-.192.316q-1.048.724-2.264 1.12q-1.217.396-2.57.396");
}

</style>
