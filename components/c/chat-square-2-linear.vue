<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pw8f5c0fp"/><path class="e98791bqv"/><path class="nay7nddul"/><path class="zsv6gzbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-2-linear" /></template>
<style>
.e98791bqv {
  stroke-linecap: round;
  d: path("M7 18L7 15");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nay7nddul {
  stroke-linecap: round;
  d: path("M12 18V12");
}

.pw8f5c0fp {
  d: path("M2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12Z");
}

.zsv6gzbnj {
  stroke-linecap: round;
  d: path("M17 18V9");
}

</style>
