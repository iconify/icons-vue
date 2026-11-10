<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g5bvm3bji"/><path class="po168nbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-wine-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g5bvm3bji {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 1C9.552 1 10 1.448 10 2V6.697L11.832 9.445C11.942 9.61 12 9.803 12 10V22C12 22.552 11.552 23 11 23H3C2.448 23 2 22.552 2 22V10C2 9.803 2.058 9.61 2.168 9.445L4 6.697V2C4 1.448 4.448 1 5 1H9ZM19 16V21H22V23H14V21H17V16H19Z");
}

.po168nbje {
  d: path("M12 13V22C12 22.552 11.552 23 11 23H3C2.448 23 2 22.552 2 22V13H12ZM21 9C21.552 9 22 9.448 22 10V13C22 15.209 20.209 17 18 17C15.791 17 14 15.209 14 13V10C14 9.448 14.448 9 15 9H21Z");
}

</style>
