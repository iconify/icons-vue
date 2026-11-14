<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ext2x-bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:edit-lock" /></template>
<style>
.ext2x-bpn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.833 4.46l.707.707q1.591 1.59 0 3.181l-5.689 5.689q-.481.482-1.149.615l-1.323.265q-1.024.205-1.763-.533q-.738-.739-.533-1.763l.265-1.323q.133-.668.615-1.149l5.689-5.689q1.591-1.591 3.181 0M17.5 15.25h2v-.5q0-.414-.293-.707t-.707-.293q-1 0-1 1zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-1q0-1.768 1.25-2.286v-.714q0-2.5 2.5-2.5q1.036 0 1.768.732T21 14.75z");
}

</style>
