<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="s1dqcacah"/><circle class="ons53cb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hubcap-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

.s1dqcacah {
  d: path("M16.75 12h2m-3.39 3.36l1.41 1.41M12 16.75v2m-3.36-3.39l-1.41 1.41M7.25 12h-2m3.39-3.36L7.23 7.23m4.77.02v-2m3.36 3.39l1.41-1.41");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
