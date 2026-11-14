<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z70z739fx"/><path class="jokbfqx7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-subscriptions" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jokbfqx7c {
  d: path("m3 6.5l7.5 4l7.5-4m-7.5 4v8m5.25-4h4.5A1.75 1.75 0 0 1 22 16.25v4A1.75 1.75 0 0 1 20.25 22h-4.5A1.75 1.75 0 0 1 14 20.25v-4a1.75 1.75 0 0 1 1.75-1.75m-1.75 3h8M16.5 13v2.5m3-2.5v2.5");
}

.z70z739fx {
  d: path("m11.206 18.124l-.706.376l-7.5-4v-8l7.5-4l7.5 4v4.1");
}

</style>
