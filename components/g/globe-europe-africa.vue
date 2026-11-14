<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="tdo704kha"/><path class="nqrxs2bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:globe-europe-africa" /></template>
<style>
.nqrxs2bux {
  d: path("m11 9.5l1.5-2H16l.75 2.5l1.25.5l-.75 1.75l-1.75 4.25l-.75 1.25l-1-2.25l-.25-2.5l-1.5-1l-1-1.5Z");
}

.tdo704kha {
  d: path("M12 2.5C6.5 6 6.5 18 12 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
