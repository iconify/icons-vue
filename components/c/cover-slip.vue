<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ek_-b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cover-slip" /></template>
<style>
.d3ek_-b5n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.818 15.289q-.515 1.234.227 2.348t2.08 1.113h10.208q1.667.001 2.308-1.539l3.541-8.5q.515-1.234-.227-2.348t-2.08-1.113H8.667Q7 5.249 6.359 6.789zm6.605-2.654l1.25-2.999Q11.25 8.25 12.75 8.25H15q1.204 0 1.872 1.002t.205 2.114l-1.25 2.999q-.577 1.385-2.077 1.385H11.5q-1.204 0-1.872-1.002t-.205-2.113");
}

</style>
