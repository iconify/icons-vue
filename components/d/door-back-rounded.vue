<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2c05b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-back-rounded" /></template>
<style>
.s_2c05b6t {
  fill: currentColor;
  d: path("M4.5 20q-.213 0-.357-.143T4 19.5t.143-.357T4.5 19H6V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19h1.5q.214 0 .357.143T20 19.5t-.143.357T19.5 20zm5.809-7.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23T9 12t.23.54t.54.23t.539-.23");
}

</style>
