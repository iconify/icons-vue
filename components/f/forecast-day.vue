<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqaem0bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:forecast-day" /></template>
<style>
.zqaem0bro {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h10.25q2.123 0 3.624 1.501t1.501 3.624v8.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 16.125v-8.25q0-2.123 1.501-3.624T6.875 2.75m3.582 5.865q-.124-.603-.606-1.045q-.636-.581-1.494-.519q-.859.062-1.405.728q-.545.667-.435 1.521q.109.854.804 1.361q.533.389 1.155.388q.32-.959 1.092-1.731q.417-.417.889-.703m1.417-.537q-.253-.921-1.011-1.614q-1.111-1.018-2.614-.909T5.792 6.829q-.955 1.167-.763 2.661q.191 1.495 1.408 2.383q.334.244.688.4q-.875.676-.875 2.227q0 2.75 2.75 2.75h7.5q2.75 0 2.75-2.75q0-2.374-2.049-2.699q-.205-1.419-1.269-2.483Q14.614 8 12.75 8q-.454 0-.876.078");
}

</style>
