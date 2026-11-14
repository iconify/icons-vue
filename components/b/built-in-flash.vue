<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5rmxjbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:built-in-flash" /></template>
<style>
.c5rmxjbkb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.242 6.653q-1.697.523-2.319-1.139q-.267-.711.068-1.392t1.059-.903l4.458-1.372q1.697-.523 2.319 1.139q.267.711-.068 1.392t-1.059.903l-1.45.446V8.25H18q1.76 0 3.005 1.245T22.25 12.5v5q0 1.76-1.245 3.005T18 21.75H6q-1.76 0-3.005-1.245T1.75 17.5v-5q0-1.76 1.245-3.005T6 8.25h1.75V6.189zM13.5 11.25q-3.75 0-3.75 3.75t3.75 3.75T17.25 15t-3.75-3.75");
}

</style>
