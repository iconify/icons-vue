<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnqwcj8qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:access-point" /></template>
<style>
.fnqwcj8qb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.625 14.5h10.75A2.625 2.625 0 0 1 20 17.125v.25A2.625 2.625 0 0 1 17.375 20H6.625A2.625 2.625 0 0 1 4 17.375v-.25A2.625 2.625 0 0 1 6.625 14.5m2.547-5.328a4 4 0 0 1 5.656 0M6.343 6.343a8 8 0 0 1 11.314 0M7.5 17.25h.01");
}

</style>
