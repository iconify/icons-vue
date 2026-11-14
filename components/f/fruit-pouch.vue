<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrha0zb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fruit-pouch" /></template>
<style>
.vrha0zb8d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 1.75h1q1.036 0 1.768.732T15 4.25q0 .567-.22 1.044q1.715.195 3.114 1.267Q19.75 7.984 19.75 10v10q0 2.25-2.25 2.25h-11q-2.25 0-2.25-2.25V10q0-2.016 1.856-3.439Q7.505 5.489 9.22 5.294Q9 4.817 9 4.25q0-2.5 2.5-2.5m2.135 9.586l.603-.517q.056-.048.102-.106t.079-.124t.053-.137t.026-.144t-.003-.147t-.032-.144t-.059-.135t-.085-.12t-.106-.102q-.058-.045-.124-.079q-.066-.033-.137-.053t-.144-.026t-.147.003t-.144.032t-.135.059t-.12.085l-1.546 1.324Q8 11.144 8 15q0 4 4 4t4-4q0-1.657-1.172-2.828q-.544-.545-1.193-.836");
}

</style>
