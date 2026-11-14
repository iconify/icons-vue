<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkev24b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-pool" /></template>
<style>
.lkev24b9p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 2.75q-2.75 0-2.75 2.75T8.5 8.25t2.75-2.75T8.5 2.75m4.25 2.75q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75m6.75 14.25h-1.317q-.341 1.75-2.433 1.75t-2.433-1.75H9.892q-.173.566-.624 1.018q-.732.732-1.768.732q-2.092 0-2.433-1.75H4.5q-1.75 0-1.75-1.75v-2.5q0-2.25 2.25-2.25h.838l1.521-2.39q.625-1.069 1.866-1.11h4.55q1.241.041 1.866 1.11l1.521 2.39H19q2.25 0 2.25 2.25V18q0 1.75-1.75 1.75m-9.608-1.5q-.173-.566-.624-1.018Q8.536 16.5 7.5 16.5q-2.092 0-2.433 1.75H4.5q-.25 0-.25-.25v-2.5q0-.75.75-.75h1.25q.095 0 .186-.024q.092-.023.175-.069q.083-.045.152-.11t.12-.144l1.75-2.75l.017-.028q.205-.357.614-.375h4.472q.409.018.614.375l.017.028l1.75 2.75q.051.079.12.144t.152.11t.175.069t.186.024H19q.75 0 .75.75V18q0 .25-.25.25h-1.317q-.341-1.75-2.433-1.75t-2.433 1.75z");
}

</style>
