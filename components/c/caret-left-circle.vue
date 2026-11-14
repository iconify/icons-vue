<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b70pa6vue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-left-circle" /></template>
<style>
.b70pa6vue {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m4.942 5.507l1.631-1.334q1.102-.902 2.389-.292Q15 9.241 15 10.665v2.67q0 1.424-1.286 2.033q-1.287.61-2.389-.292l-1.631-1.335q-.825-.675-.825-1.741t.825-1.741");
}

</style>
