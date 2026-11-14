<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc4pnjb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conflict-of-interest" /></template>
<style>
.dc4pnjb-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-3.25 0h6.5M5.5 10l13-5M3 14.5L5.5 10L8 14.5za2.5 2.5 0 0 0 5 0m8-5L18.5 5L21 9.5zq0 .176.025.35q.024.175.073.344t.121.329t.166.31t.207.283q.114.134.246.251q.131.117.278.215q.146.097.305.173m1.63.183q.103-.023.204-.055q.1-.031.198-.072q.097-.04.191-.088t.183-.104t.174-.119t.163-.134t.151-.146q.072-.077.138-.159q.066-.083.124-.17q.059-.088.11-.18t.094-.188t.078-.196t.062-.202t.044-.206t.026-.209T21 9.5m-3 5V18m0 3h.01");
}

</style>
