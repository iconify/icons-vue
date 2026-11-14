<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e975pw2wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bias-tape" /></template>
<style>
.e975pw2wo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.427 14.75q.361-.285.7-.623Q16.25 12.003 16.25 9t-2.123-5.127T9 1.75T3.873 3.873T1.75 9t2.123 5.127q1.982 1.981 4.73 2.114l3.283 4.689q.051.074.119.134q.068.059.149.101t.168.064q.088.021.178.021H21q.236 0 .43-.136q.122-.085.202-.211t.107-.273t-.007-.292q-.032-.146-.118-.268l-3.5-5q-.051-.074-.119-.134q-.068-.059-.149-.101t-.168-.064q-.088-.021-.178-.021zm-6.726-3.451Q5.75 10.347 5.75 9t.951-2.299Q7.653 5.749 9 5.749t2.299.952T12.25 9q.001 1.346-.951 2.299T9 12.251t-2.299-.952");
}

</style>
