<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqzpl-bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:haptics-off" /></template>
<style>
.dqzpl-bqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.305 5.273q.232-.186.492-.331q.259-.144.54-.243q.28-.099.573-.149t.59-.05h1q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T16 8v4.042m-1.235 6.626q-.235.2-.502.355q-.267.156-.556.262t-.594.161q-.304.054-.613.054h-1q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177t-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T8 16v-4.027m-3.25 3.408a8 8 0 0 1 0-6.762m14.5 0a8 8 0 0 1 0 6.762M3.5 3.5l17 17");
}

</style>
