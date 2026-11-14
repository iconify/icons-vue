<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c4etvrbfw"/><path class="v7lv0dbmu"/><path class="ue3h1_b2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consultation-room" /></template>
<style>
.c4etvrbfw {
  fill: currentColor;
  d: path("M2.5 15h19v2h-19Z");
}

.ue3h1_b2y {
  fill: currentColor;
  d: path("M5.25 5.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7lv0dbmu {
  d: path("M4.5 17v4.5m15-4.5v4.5M4.552 9.441q.191.192.417.343t.476.256q.251.104.517.157t.538.053q.161 0 .321-.019t.317-.056q.157-.038.308-.093q.152-.055.296-.128t.278-.162t.257-.193q.123-.105.233-.223q.11-.117.206-.247m-.848-4.014q-.182-.105-.379-.181m-1.923-.021q-.197.072-.381.172M2.5 15c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75m4.25-7.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM13.5 15c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75");
}

</style>
