<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="diid31b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gif-outline-rounded" /></template>
<style>
.diid31b7s {
  fill: currentColor;
  d: path("M11.934 14.567q-.126-.125-.126-.317v-4.5q0-.192.125-.317t.316-.125t.317.125t.126.317v4.5q0 .192-.125.317t-.316.125t-.317-.125m-5.011.125q-.565 0-.975-.418t-.41-.966v-2.616q0-.548.41-.966t.975-.418h2.558q.192 0 .317.125t.125.316t-.125.317t-.317.126H7.039q-.231 0-.423.192q-.193.193-.193.424v2.384q0 .231.193.423q.192.193.423.193h1.384q.23 0 .423-.193q.193-.192.193-.423v-.596q0-.192.125-.317t.316-.125t.317.122t.126.31v.722q0 .548-.41.966t-.974.418zm7.78-.125q-.126-.125-.126-.317v-4.5q0-.192.125-.317t.317-.125h3q.192 0 .317.125t.126.316t-.126.317t-.317.126h-2.557v1.462h1.557q.192 0 .317.125q.126.125.126.316t-.126.318t-.317.126h-1.557v1.711q0 .192-.125.317t-.317.125t-.317-.125");
}

</style>
