<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="try0bmbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-heart" /></template>
<style>
.try0bmbic {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.201 4.953l-4.5 3.937Q3.25 10.16 3.25 12.088V16.5q0 1.76 1.245 3.005T7.5 20.75h9q1.76 0 3.005-1.245T20.75 16.5v-4.412q0-1.928-1.451-3.198l-4.5-3.937q-2.799-2.45-5.598 0m2.421 13.195Q8.25 16.181 8.25 13.75q0-2.5 2.5-2.5q.741 0 1.25.357q.509-.357 1.25-.357q2.5 0 2.5 2.5q0 2.431-3.372 4.398q-.086.05-.182.076T12 18.25t-.196-.026t-.182-.076");
}

</style>
