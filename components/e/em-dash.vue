<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2_q0pb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:em-dash" /></template>
<style>
.i2_q0pb4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 9.75h16q2.25 0 2.25 2.25T20 14.25H4q-2.25 0-2.25-2.25T4 9.75");
}

</style>
