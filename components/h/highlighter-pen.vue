<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bdpe8qskd"/><path class="abmj84dup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:highlighter-pen" /></template>
<style>
.abmj84dup {
  d: path("m11.111 12.182l1.061 1.061a1 1 0 0 1 0 1.414l-.12.119a1.5 1.5 0 0 1-1.398.401l-1.593-.368a1.247 1.247 0 0 1-.602-2.097l.531-.53a1.5 1.5 0 0 1 2.121 0M3 19.5h11");
}

.bdpe8qskd {
  d: path("m18.27 5.199l.531.531a2.625 2.625 0 0 1 0 3.712l-3.359 3.359a2.625 2.625 0 0 1-3.712 0l-.531-.531a2.625 2.625 0 0 1 0-3.712l3.359-3.359a2.625 2.625 0 0 1 3.712 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
