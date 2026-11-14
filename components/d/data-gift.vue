<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="grg1wsbqy"/><path class="j0l694ozk"/><path class="s1fwn9buu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-gift" /></template>
<style>
.grg1wsbqy {
  d: path("M3 7.5h16v4H3ZM12.8 21H4.5v-9.5h13v.2M11 7.5V21m0-13.5c-2.5-4.5-5.5-3-3.5 0m3.5 0c2.5-4.5 5.5-3 3.5 0");
}

.j0l694ozk {
  d: path("M15.5 15.75a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0Z");
}

.s1fwn9buu {
  d: path("M15.5 15.75V20a3 1.25 0 0 0 6 0v-4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
