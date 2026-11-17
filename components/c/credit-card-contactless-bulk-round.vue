<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n3ea6gw5u"/><path class="jmcgelb7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-contactless-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jmcgelb7n {
  d: path("M14.832 7.445a8.2 8.2 0 0 1 1.034 6.911a8.2 8.2 0 0 1-1.034 2.199a1 1 0 0 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1 1 0 0 1 1.664-1.11m-2.42 3.234a4.6 4.6 0 0 1-.58 3.876a1 1 0 0 1-1.664-1.11a2.61 2.61 0 0 0 0-2.89a1 1 0 0 1 1.664-1.11c.254.38.449.796.58 1.234M8.01 11a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Z");
}

.n3ea6gw5u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Z");
}

</style>
