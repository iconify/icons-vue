<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="buoz0ulwf"/><path class="p_q1scbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-end-sharp-duotone" /></template>
<style>
.buoz0ulwf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 13C16.552 13 17 13.448 17 14V20C17 20.552 16.552 21 16 21H8C7.448 21 7 20.552 7 20V14C7 13.448 7.448 13 8 13H16ZM20 3C20.552 3 21 3.448 21 4V10C21 10.552 20.552 11 20 11H4C3.448 11 3 10.552 3 10V4C3 3.448 3.448 3 4 3H20Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p_q1scbzh {
  d: path("M23 19V21H1V19H23ZM23 9V11H1V9H23Z");
}

</style>
