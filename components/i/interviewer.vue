<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2fzcj2vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:interviewer" /></template>
<style>
.u2fzcj2vs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.75H20q2.25 0 2.25 2.25v6q0 2.25-2.25 2.25h-3.26l-3.304 2.36q-.06.043-.128.074q-.067.03-.139.047q-.072.016-.146.019q-.073.002-.146-.01t-.142-.038t-.132-.066q-.063-.039-.117-.089q-.053-.051-.096-.111q-.14-.196-.14-.436V4q0-2.25 2.25-2.25M3.25 9q0-3.75 3.75-3.75T10.75 9T7 12.75q-1.875 0-2.812-.937Q3.25 10.875 3.25 9m-.019 7.078Q1.75 17.639 1.75 20q0 1.75 1.75 1.75h7q1.75 0 1.75-1.75q0-2.361-1.481-3.922Q9.273 14.5 7 14.5t-3.769 1.578");
}

</style>
