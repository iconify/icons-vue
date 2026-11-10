<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d1rf12b4i"/><path class="nd5z7n66w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-space-around-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d1rf12b4i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 8C16.6489 8 18 9.341 18 11V13C18 14.657 16.656 16 15 16H9C7.3449 16 6 14.667 6 13V11C6 9.356 7.3327 8 9 8H15Z");
}

.nd5z7n66w {
  d: path("M22 19C22.5523 19 23 19.448 23 20C23 20.552 22.5523 21 22 21H2C1.4477 21 1 20.552 1 20C1 19.448 1.4477 19 2 19H22ZM22 3C22.5523 3 23 3.448 23 4C23 4.552 22.5523 5 22 5H2C1.4477 5 1 4.552 1 4C1 3.448 1.4477 3 2 3H22Z");
}

</style>
