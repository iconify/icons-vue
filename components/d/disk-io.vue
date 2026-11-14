<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="febtztbhs"/><path class="m1xpcfb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disk-io" /></template>
<style>
.febtztbhs {
  d: path("M14.299 17.718q-.113.202-.253.387q-.139.185-.302.35t-.345.308t-.383.259t-.414.206t-.437.15t-.454.091q-.229.031-.461.031H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 2.5h5.25q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34t.017.343v7.292");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1xpcfb1n {
  d: path("M5 9.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m3.75 0h.01m8.74 12v-7m-1.25 1.25l1.25-1.25l1.25 1.25m1.75-1.25v7m-1.25-1.25l1.25 1.25l1.25-1.25");
}

</style>
