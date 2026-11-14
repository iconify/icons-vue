<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj8gp91zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garage" /></template>
<style>
.wj8gp91zt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.216 9.883q-.966.75-.966 1.973v6.894q0 2.5 2.5 2.5H8.5q-2.25 0-2.25-2.25v-5q0-2.25 2.25-2.25h7q2.25 0 2.25 2.25v5q0 2.25-2.25 2.25h3.75q1.036 0 1.768-.732t.732-1.768v-6.894q0-1.223-.966-1.973l-7.25-5.639q-1.534-1.193-3.068 0z");
}

</style>
