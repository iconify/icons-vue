<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyyy9geps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:full-time-job" /></template>
<style>
.jyyy9geps {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m1.061 13.435Q3.25 15.624 3.25 12t2.563-6.187T12 3.25t6.187 2.563T20.75 12t-2.563 6.187T12 20.75t-6.187-2.563M12 4.25q3.21 0 5.48 2.27T19.75 12t-2.27 5.48T12 19.75t-5.48-2.27T4.25 12t2.27-5.48T12 4.25m-.75 8.5V8h1.5v2.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.25v1.5z");
}

</style>
