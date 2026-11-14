<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlwn2o42d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cosmetics-store" /></template>
<style>
.mlwn2o42d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 14.826q1.5.337 1.5 2.174v3q0 2.25-2.25 2.25h-5q-2.25 0-2.25-2.25v-3q0-1.837 1.5-2.174V12.75q0-.06.01-.119q.009-.06.028-.117t.047-.11q.027-.053.063-.102t.079-.09t.093-.076t.103-.061t.111-.043l5-1.5q.143-.043.292-.028q.148.015.28.086q.131.07.225.186q.095.116.137.258q.032.106.032.216zm-5-1.518v1.442h3.5v-2.492zM2.311 6.205q-.061.141-.061.295q.001 2.999 3 2.999q1.499 0 2.249-.75q.75.751 2.251.751T12 8.75q.75.75 2.25.75t2.251-.751q.75.749 2.249.749q2.998 0 3-2.997v-.022z");
}

</style>
