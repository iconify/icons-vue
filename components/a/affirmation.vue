<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3q5o2bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:affirmation" /></template>
<style>
.q3q5o2bok {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm5.107 10.889Q8 11.419 8 8.75q0-2.5 2.5-2.5q.89 0 1.5.523q.61-.523 1.5-.523q2.5 0 2.5 2.5q0 2.669-3.607 4.889q-.089.054-.189.083q-.1.028-.204.028t-.204-.028t-.189-.083");
}

</style>
