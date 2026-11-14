<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4jfo7fqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aircraft-window" /></template>
<style>
.q4jfo7fqr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.48 4.02Q15.21 1.75 12 1.75T6.52 4.02T4.25 9.5v5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48v-5q0-3.21-2.27-5.48M8.5 15.75q-.205 0-.382-.105q-1.573-.931-1.162-2.713q.345-1.497 1.687-1.84q.646-2.077 2.974-2.299q2.403-.229 3.42 1.821q1.563.493 1.795 2.233q.26 1.947-1.497 2.824q-.158.079-.335.079z");
}

</style>
