<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ji74krb5c"/><path class="ceowdjn6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:competition-law" /></template>
<style>
.ceowdjn6w {
  d: path("M5 21v-4h3v4m7.5 0v-5.5h3V21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ji74krb5c {
  d: path("M3 21V11l1.5-2.5h4L10 11v10Zm10 0V8l1.5-3.5h5L21 8v13Z");
}

</style>
