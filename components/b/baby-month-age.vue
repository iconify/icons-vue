<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k-j1jgsga"/><path class="iw1cfbheh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-month-age" /></template>
<style>
.iw1cfbheh {
  d: path("m5.862 3.302l7.336 1.56l-1.56 7.336l-7.336-1.56ZM16.5 16l2-1.5V21m-2 0h4");
}

.k-j1jgsga {
  d: path("M13.5 16.6V21h-11v-9h11v2.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
