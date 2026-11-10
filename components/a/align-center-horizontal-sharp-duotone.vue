<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ybdng3b0t"/><path class="ctw-32afx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-horizontal-sharp-duotone" /></template>
<style>
.ctw-32afx {
  d: path("M4 11V13H1V11H4ZM14 11V13H10V11H14ZM23 11V13H20V11H23Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ybdng3b0t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 3C20.552 3 21 3.4477 21 4V20C21 20.5523 20.552 21 20 21H14C13.448 21 13 20.5523 13 20V4C13 3.4477 13.448 3 14 3H20ZM10 7C10.552 7 11 7.4477 11 8V16C11 16.5523 10.552 17 10 17H4C3.448 17 3 16.5523 3 16V8C3 7.4477 3.448 7 4 7H10Z");
}

</style>
