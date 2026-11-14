<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jo0enbkij"/><path class="clxk-sb_d"/><path class="lxczy9weo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layers-triple" /></template>
<style>
.clxk-sb_d {
  d: path("m2.5 12l9.5 5.5l9.5-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo0enbkij {
  d: path("m12.752 2.935l6.506 3.767a1.5 1.5 0 0 1 0 2.596l-6.506 3.767a1.5 1.5 0 0 1-1.504 0L4.742 9.298a1.5 1.5 0 0 1 0-2.596l6.506-3.767a1.5 1.5 0 0 1 1.504 0");
}

.lxczy9weo {
  d: path("m2.5 16l9.5 5.5l9.5-5.5");
}

</style>
