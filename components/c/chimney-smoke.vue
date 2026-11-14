<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb1ltxbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chimney-smoke" /></template>
<style>
.hb1ltxbgp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 4q0-2 2-2t2 2t-2 2t-2-2m6.75-1.25Q12.5 2.75 12.5 5t2.25 2.25T17 5t-2.25-2.25M17.25 7q0-2.5 2.5-2.5q1.036 0 1.768.732T22.25 7t-.732 1.768t-1.768.732q-2.5 0-2.5-2.5m-5.5 2.375q0-1.875-1.875-1.875h-3.75Q4.25 7.5 4.25 9.375q0 1.309.914 1.704l-1.407 10.32q-.007.05-.007.101q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014h7q.051 0 .101-.007q.148-.02.277-.095t.219-.194t.128-.263t.018-.292l-1.407-10.32q.914-.395.914-1.704");
}

</style>
