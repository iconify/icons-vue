<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lwo9wtbpb"/><path class="kjwhxvqfn"/><path class="llzzoib2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:defibrillator" /></template>
<style>
.kjwhxvqfn {
  d: path("M12 17.5s-4.5-2.75-4.5-5.75C7.5 10.25 8.6 9 10 9c.9 0 1.6.5 2 1.25C12.4 9.5 13.1 9 14 9c1.4 0 2.5 1.25 2.5 2.75c0 3-4.5 5.75-4.5 5.75Z");
}

.llzzoib2n {
  d: path("M12.75 10.75L11 13.25h2l-1.75 2.5");
}

.lwo9wtbpb {
  d: path("M4 4.5h16a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-14a1 1 0 0 1 1-1Zm5 0v-2h6v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
