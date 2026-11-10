<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="htjue96hg"/><path class="y0cofcb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-vertical-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.htjue96hg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 13C20.552 13 21 13.448 21 14V20C21 20.552 20.552 21 20 21H4C3.448 21 3 20.552 3 20V14C3 13.448 3.448 13 4 13H20ZM16 3C16.552 3 17 3.448 17 4V10C17 10.552 16.552 11 16 11H8C7.448 11 7 10.552 7 10V4C7 3.448 7.448 3 8 3H16Z");
}

.y0cofcb0f {
  d: path("M13 20V23H11V20H13ZM13 10V14H11V10H13ZM13 1V4H11V1H13Z");
}

</style>
