<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1tnh5bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:co2-jet" /></template>
<style>
.a1tnh5bcg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.054 6q.311-2.01 2.416-2.224q.858-1.956 3.155-1.956t3.155 1.956q2.47.252 2.47 2.974q0 3-3 3H14q-2.598 0-2.946-2.25H9.25v2.384q.399.254.755.611Q11.25 11.74 11.25 13.5V18q0 1.76-1.245 3.005T7 22.25t-3.005-1.245T2.75 18v-4.5q0-1.76 1.245-3.005q.356-.357.755-.611V6.75q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5.5 6zM6.25 9.31q.363-.06.75-.06t.75.06V7.5h-1.5z");
}

</style>
