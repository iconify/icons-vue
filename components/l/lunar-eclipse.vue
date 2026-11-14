<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rof7mbbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lunar-eclipse" /></template>
<style>
.rof7mbbxo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M8.985 8.16q-.148-2.776 1.599-4.939q.093-.116.135-.259t.027-.291t-.087-.28t-.188-.225t-.259-.135t-.291-.027t-.28.087t-.225.188Q7.309 4.889 7.487 8.24q.178 3.35 2.55 5.723q2.373 2.372 5.723 2.55q3.351.178 5.961-1.929q.058-.047.105-.104t.083-.121t.057-.136q.022-.07.03-.144t.001-.147t-.028-.144t-.055-.136q-.034-.066-.08-.123q-.094-.116-.225-.188q-.131-.071-.28-.087q-.148-.016-.291.027t-.259.135q-2.163 1.747-4.939 1.599q-2.776-.147-4.742-2.113T8.985 8.16");
}

</style>
