<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yufdzrkxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:district-heating-plant" /></template>
<style>
.yufdzrkxk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 3.25h-11q-1.76 0-3.005 1.245T2.25 7.5v8q0 1.76 1.245 3.005q.777.777 1.755 1.069V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T6.75 21v-1.25h10.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.426q.978-.292 1.755-1.069Q21.75 17.26 21.75 15.5v-8q0-1.76-1.245-3.005T17.5 3.25");
}

</style>
