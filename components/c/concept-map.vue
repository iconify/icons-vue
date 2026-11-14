<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sukphndip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:concept-map" /></template>
<style>
.sukphndip {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 3Q2 3 2 5.5T4.5 8q.658 0 1.193-.295l2.985 2.189Q8.25 10.733 8.25 12t.428 2.106l-2.985 2.189Q5.158 16 4.5 16Q2 16 2 18.5T4.5 21q1.036 0 1.768-.732T7 18.5q0-.611-.255-1.116l2.957-2.169q.882.535 2.298.535t2.298-.535l2.885 2.116Q17 17.824 17 18.5q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5q-.756 0-1.284.229l-2.894-2.123q.428-.839.428-2.106t-.428-2.106l2.894-2.123Q18.744 8 19.5 8Q22 8 22 5.5T19.5 3T17 5.5q0 .676.183 1.169l-2.885 2.116Q13.416 8.25 12 8.25t-2.298.535L6.745 6.616Q7 6.111 7 5.5q0-1.036-.732-1.768T4.5 3");
}

</style>
