<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyz4tjbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copper-ore" /></template>
<style>
.oyz4tjbcy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.724 11.74q-.591 1.377.345 2.547l4.743 5.929q.861 1.075 2.229.922l7.027-.781q1.449-.16 2.023-1.5l2.318-5.408q.401-.935.036-1.883l-1.966-5.11q-.399-1.037-1.436-1.436l-5.12-1.969q-.934-.359-1.858.026L6.368 5.035q-.937.39-1.337 1.323zM11.5 8.749q0-1.035.732-1.767q.732-.733 1.768-.733t1.768.733q.733.732.732 1.767q.001 1.037-.732 1.769q-.732.733-1.768.733t-1.768-.733t-.732-1.767zM6 12.5Q6 10 8.5 10t2.5 2.5T8.5 15T6 12.5m6.25 2.5q0-2.25 2.25-2.25T16.75 15t-2.25 2.25T12.25 15");
}

</style>
