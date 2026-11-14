<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etpo0fmni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hot-topic" /></template>
<style>
.etpo0fmni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.384 20.313q3.993 2.426 8.36.573q4.527-1.922 5.465-6.75T18.67 5.83q-3.478-3.477-8.306-2.539t-6.75 5.465q-1.853 4.367.573 8.36l-.908 3.178q-.059.206 0 .412q.02.071.054.137q.034.065.08.123t.102.106t.121.084q.064.035.135.058q.07.023.143.031q.074.009.147.002q.074-.006.145-.026zM12 16.25q-4 0-4-3.5q0-1.35 1.24-3.033q.844-1.146 1.032-1.899q.018-.072.05-.138q.031-.067.075-.126q.044-.06.099-.109q.055-.05.118-.088t.133-.063t.143-.036t.146-.007q.074.003.146.021q.201.051.348.198q.642.642.946 1.448q.024-.085.024-.168q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T13.25 8q.128 0 .248.042q.121.043.221.122Q16 9.99 16 12.75q0 3.5-4 3.5");
}

</style>
