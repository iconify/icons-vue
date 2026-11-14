<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uupfqtbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bocce" /></template>
<style>
.uupfqtbdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 7q0-1.76 1.245-3.005T12 2.75t3.005 1.245T16.25 7t-1.245 3.005T12 11.25t-3.005-1.245T7.75 7m-5.5 9.5q0-1.76 1.245-3.005T6.5 12.25t3.005 1.245T10.75 16.5t-1.245 3.005T6.5 20.75t-3.005-1.245T2.25 16.5m12.245-3.005Q13.25 14.74 13.25 16.5t1.245 3.005T17.5 20.75t3.005-1.245T21.75 16.5t-1.245-3.005T17.5 12.25t-3.005 1.245");
}

</style>
