<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b6ykfgals"/><path class="rng-7r_uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-vertical-sharp-duotone" /></template>
<style>
.b6ykfgals {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 13C22.552 13 23 13.448 23 14V20C23 20.552 22.552 21 22 21H6C5.448 21 5 20.552 5 20V14C5 13.448 5.448 13 6 13H22ZM14 3C14.552 3 15 3.448 15 4V10C15 10.552 14.552 11 14 11H6C5.448 11 5 10.552 5 10V4C5 3.448 5.448 3 6 3H14Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rng-7r_uq {
  d: path("M3 1V23H1V1H3Z");
}

</style>
