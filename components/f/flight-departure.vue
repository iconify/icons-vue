<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcof3lb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flight-departure" /></template>
<style>
.jcof3lb_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.34 5.58l-.43 1.59q-.16.58-.61.98l-1.35 1.2q-.45.4-.3.98l1.45 5.59q.15.58-.27 1l-.16.16q-.42.42-.72-.1l-2.4-4.21q-.3-.52-.72-.1l-1.91 1.91Q9.5 15 9.5 15.6v1.05q0 .6-.36 1.08l-.03.04q-.36.48-.63-.06l-.96-1.92q-.27-.54-.81-.81l-1.92-.96q-.54-.27-.06-.63l.04-.03Q5.25 13 5.85 13H6.9q.6 0 1.02-.42l1.91-1.91q.42-.42-.1-.72l-4.21-2.4q-.52-.3-.1-.72l.16-.16q.42-.42 1-.27l5.59 1.45q.58.15.98-.3l1.2-1.35q.4-.45.98-.61l1.59-.43q.58-.16.42.42M3.75 20.75h16.5");
}

</style>
