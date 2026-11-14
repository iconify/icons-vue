<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yshwvi3au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:firewood-bag" /></template>
<style>
.yshwvi3au {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.5 9.75h-1.25V4q0-1.75-1.75-1.75h-1Q9.75 2.25 9.75 4v5.75H8.5V7q0-1.75-1.75-1.75h-1Q4 5.25 4 7v2.75q-.099 0-.195.026t-.181.075t-.156.12t-.119.157q-1.869 3.27-1.214 7.305Q2.916 22.25 7 22.25h10q4.084 0 4.865-4.817q.655-4.035-1.214-7.305q-.049-.086-.119-.157q-.07-.07-.156-.12t-.181-.075T20 9.75V7q0-1.75-1.75-1.75h-1Q15.5 5.25 15.5 7zm1.5 0h1.5V7q0-.25-.25-.25h-1Q17 6.75 17 7zm-4.25 0h-1.5V4q0-.25.25-.25h1q.25 0 .25.25zm-7.25 0H7V7q0-.25-.25-.25h-1q-.25 0-.25.25z");
}

</style>
