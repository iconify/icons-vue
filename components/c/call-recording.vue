<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrihuxwad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:call-recording" /></template>
<style>
.nrihuxwad {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 1.75q2.75 0 2.75 2.75q0 6.686-4.532 11.218T4.5 20.25q-2.75 0-2.75-2.75v-3q0-.059.009-.117t.027-.113q.018-.056.045-.109q.026-.052.061-.1q.034-.047.075-.089t.089-.076t.099-.062t.108-.046l4.5-1.5q.055-.018.113-.028q.058-.009.117-.01t.117.008t.114.026t.108.044q.053.026.101.059q.048.034.09.075t.077.088l1.147 1.53q3.668-1.665 5.333-5.333L12.55 7.6q-.047-.035-.088-.077t-.075-.09t-.059-.101q-.026-.052-.044-.108t-.026-.114t-.008-.117t.01-.117t.028-.113l1.5-4.5q.019-.056.046-.108t.062-.099t.076-.089t.089-.075q.048-.035.1-.061q.053-.027.109-.045q.055-.018.113-.027t.117-.009zm-1.75 17.5q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m1.5 0q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
