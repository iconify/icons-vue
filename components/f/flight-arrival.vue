<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqpkaopcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flight-arrival" /></template>
<style>
.tqpkaopcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.92 15.84l-1.59-.43q-.58-.16-.98-.61l-1.2-1.35q-.4-.45-.98-.3L6.58 14.6q-.58.15-1-.27l-.16-.16q-.42-.42.1-.72l4.21-2.4q.52-.3.1-.72L7.92 8.42Q7.5 8 6.9 8H5.85q-.6 0-1.08-.36l-.04-.03q-.48-.36.06-.63l1.92-.96q.54-.27.81-.81l.96-1.92q.27-.54.63-.06l.03.04q.36.48.36 1.08V5.4q0 .6.42 1.02l1.91 1.91q.42.42.72-.1l2.4-4.21q.3-.52.72-.1l.16.16q.42.42.27 1l-1.45 5.59q-.15.58.3.98l1.35 1.2q.45.4.61.98l.43 1.59q.16.58-.42.42M3.75 20.75h16.5");
}

</style>
