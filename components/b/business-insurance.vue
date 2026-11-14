<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z18iuql2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:business-insurance" /></template>
<style>
.z18iuql2k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 6.25h1.25q1.76 0 3.005 1.245T21.75 10.5v6q0 1.76-1.245 3.005T17.5 20.75h-11q-1.76 0-3.005-1.245T2.25 16.5v-6q0-1.76 1.245-3.005T6.5 6.25h1.25V5.5q0-2.25 2.25-2.25h4q.932 0 1.591.659T16.25 5.5zm-7 0V5.5q0-.75.75-.75h4q.75 0 .75.75v.75zm2.987 3.038Q12.122 9.25 12 9.25t-.237.038l-3 1q-.056.019-.108.046t-.099.062q-.048.035-.089.076q-.041.042-.075.089q-.035.048-.061.1q-.027.053-.045.109q-.018.055-.027.113T8.25 11v2q0 2.959 3.455 4.439q.141.061.295.061t.295-.061Q15.75 15.959 15.75 13v-2q0-.059-.009-.117t-.027-.113q-.018-.056-.045-.109q-.026-.052-.061-.1q-.034-.047-.075-.089t-.089-.076q-.047-.035-.099-.062t-.108-.046z");
}

</style>
