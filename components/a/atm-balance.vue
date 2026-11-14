<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wffwdccte"/><path class="jy45ur0ip"/><path class="pn8692y0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-balance" /></template>
<style>
.jy45ur0ip {
  d: path("M7 4.25h10v7.25H7Z");
}

.pn8692y0e {
  d: path("M11 6.5c0-.3-.43-.5-1-.5c-.7 0-1.12.35-1 1c-.12.92 2.12.47 2 2c.12.38-.35.75-1 .75c-.6 0-1.03-.25-1-.75m1-3.75V6m0 3.75v.75M12.5 8h2m-8 6.25h11M7 17.75h.01m2.74 0h.01m2.74 0h.01m2.74 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wffwdccte {
  d: path("M4 2.5h16v19H4Z");
}

</style>
