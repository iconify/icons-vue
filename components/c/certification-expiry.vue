<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jyw1v813i"/><path class="qakcsxr8q"/><path class="vucp2m5ge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:certification-expiry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyw1v813i {
  d: path("M8.582 3.077za1.44 1.44 0 0 0 1.375.368a.83.83 0 0 1 1.009.582a1.44 1.44 0 0 0 1.007 1.007a.83.83 0 0 1 .582 1.009a1.44 1.44 0 0 0 .368 1.375a.83.83 0 0 1 0 1.164a1.44 1.44 0 0 0-.368 1.375a.83.83 0 0 1-.582 1.009a1.44 1.44 0 0 0-1.007 1.007a.83.83 0 0 1-1.009.582a1.44 1.44 0 0 0-1.375.368a.83.83 0 0 1-1.164 0a1.44 1.44 0 0 0-1.375-.368a.83.83 0 0 1-1.009-.582a1.44 1.44 0 0 0-1.007-1.007a.83.83 0 0 1-.582-1.009a1.44 1.44 0 0 0-.368-1.375a.83.83 0 0 1 0-1.164a1.44 1.44 0 0 0 .368-1.375a.83.83 0 0 1 .582-1.009a1.44 1.44 0 0 0 1.007-1.007a.83.83 0 0 1 1.009-.582a1.44 1.44 0 0 0 1.375-.368a.83.83 0 0 1 1.164 0");
}

.qakcsxr8q {
  d: path("M5.5 12.75v7.75L7.75 19L10 20.5v-7.75M15.5 11h6m-6 10h6m-4.75-10v1.5l3.5 7V21");
}

.vucp2m5ge {
  d: path("M20.25 11v1.5l-3.5 7V21");
}

</style>
