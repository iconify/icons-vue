<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3254hb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:common-ancestor" /></template>
<style>
.s3254hb0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25Q3.25 2.25 3.25 5q0 2.397 2.089 2.705q.477 1.853 3.523 3.244Q11.25 12.04 11.25 13v8q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-8q0-.96 2.388-2.051q3.046-1.391 3.523-3.244Q20.75 7.397 20.75 5q0-2.75-2.75-2.75T15.25 5q0 2.244 1.832 2.657q-.51.988-2.567 1.928q-1.7.776-2.515 1.67q-.815-.894-2.515-1.67q-2.057-.94-2.567-1.928Q8.75 7.244 8.75 5q0-2.75-2.75-2.75");
}

</style>
