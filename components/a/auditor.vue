<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ovc5bencm"/><path class="op8q-tboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auditor" /></template>
<style>
.op8q-tboh {
  d: path("m16.75 18.25l1 1l1.75-1.75");
}

.ovc5bencm {
  d: path("M12.472 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.718 0 1.407.064 2.057.186M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8.75 8.5a1 1 0 0 1 1-1H17v-1h2.5v1h.75a1 1 0 0 1 1 1V21a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
