<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5_ej9ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guard-tower" /></template>
<style>
.ox5_ej9ym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11V6.75q0-.5-.5-.5h-.25q-.5 0-.07-.26l4.89-2.98q.43-.26.86 0l4.89 2.98q.43.26-.07.26H17q-.5 0-.5.5V11q0 .5-.5.5H8q-.5 0-.5-.5m1.5.5l-1.5 9.75M15 11.5l1.5 9.75m-8.25-5h7.5m.75-7L21.25 8m-4.75 3l4.75 1.25");
}

</style>
