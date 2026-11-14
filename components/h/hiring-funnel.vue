<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw3gcdk3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hiring-funnel" /></template>
<style>
.uw3gcdk3m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 5q0-2.25 2.25-2.25T8.75 5T6.5 7.25T4.25 5M12 2.75Q9.75 2.75 9.75 5T12 7.25T14.25 5T12 2.75M15.25 5q0-2.25 2.25-2.25T19.75 5T17.5 7.25T15.25 5M7.923 7.75q-1.693-.001-2.31 1.576q-.616 1.577.628 2.725l2.687 2.48q.322.297.322.735v3.598q0 1.168.96 1.833q.96.666 2.053.255l.864-.324q1.623-.608 1.623-2.341v-3.021q0-.438.322-.735l2.686-2.48q1.245-1.148.629-2.725t-2.31-1.576z");
}

</style>
