<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j30eue3lw"/><path class="qnlb41bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-distribute-end-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j30eue3lw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 3C20.552 3 21 3.448 21 4V20C21 20.552 20.552 21 20 21H14C13.448 21 13 20.552 13 20V4C13 3.448 13.448 3 14 3H20ZM10 7C10.552 7 11 7.448 11 8V16C11 16.552 10.552 17 10 17H4C3.448 17 3 16.552 3 16V8C3 7.448 3.448 7 4 7H10Z");
}

.qnlb41bvn {
  d: path("M11 1V23H9V1H11ZM21 1V23H19V1H21Z");
}

</style>
