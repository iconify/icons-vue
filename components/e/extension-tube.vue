<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plw4bw2rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:extension-tube" /></template>
<style>
.plw4bw2rk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.688 1.243-6.33Q4.367 2.75 6.5 2.75h11q2.133.002 3.506 2.921Q22.249 8.312 22.249 12t-1.243 6.329q-1.373 2.919-3.505 2.921H6.5q-2.133 0-3.507-2.92Q1.75 15.688 1.75 12m11.916 7.75h3.833q1.181-.001 2.15-2.06q1.1-2.338 1.1-5.69t-1.1-5.69Q18.68 4.251 17.5 4.25h-3.834q.451.593.84 1.421Q15.749 8.312 15.749 12t-1.243 6.329q-.389.828-.84 1.421m-2.667-15.5H9.168q.45.593.839 1.42Q11.25 8.312 11.25 12t-1.243 6.33q-.389.827-.839 1.42h1.831q1.181-.001 2.15-2.06q1.1-2.338 1.1-5.69t-1.1-5.69q-.969-2.059-2.15-2.06");
}

</style>
