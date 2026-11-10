<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zbuimnbgy"/><path class="bcusd-b1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-horizontal-duotone" /></template>
<style>
.bcusd-b1k {
  d: path("M22 1C22.5523 1 23 1.448 23 2C23 2.552 22.5523 3 22 3H2C1.4477 3 1 2.552 1 2C1 1.448 1.4477 1 2 1H22Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zbuimnbgy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 5C9.6569 5 11 6.343 11 8V20C11 21.657 9.6568 23 8 23H6C4.3432 23 3 21.657 3 20V8C3 6.343 4.3431 5 6 5H8ZM18 5C19.6569 5 21 6.343 21 8V12C21 13.657 19.6569 15 18 15H16C14.3431 15 13 13.657 13 12V8C13 6.343 14.3431 5 16 5H18Z");
}

</style>
