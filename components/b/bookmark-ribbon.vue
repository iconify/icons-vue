<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwuef7b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bookmark-ribbon" /></template>
<style>
.rwuef7b8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 2.25H6.25q-2.5 0-2.5 2.5v1q0 1.036.732 1.768t1.768.732h1V21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.136 0 .264-.048q.127-.048.23-.138L12 18.997l3.506 3.067q.112.099.254.146q.141.048.29.038t.282-.076q.134-.066.232-.178q.09-.103.138-.23q.048-.128.048-.264V8.25h1q1.036 0 1.768-.732t.732-1.768v-1q0-2.5-2.5-2.5m-2.5 6v11.597l-2.756-2.411q-.051-.045-.109-.08q-.058-.034-.121-.058t-.13-.036T12 17.25t-.134.012t-.13.036t-.121.058t-.109.08L8.75 19.847V8.25z");
}

</style>
