<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c-b2v6-hp"/><path clip-rule="evenodd" class="q0u8copsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iv-bag-sharp-duotone" /></template>
<style>
.c-b2v6-hp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 17H5C4.448 17 4 16.5523 4 16V2C4 1.4477 4.448 1 5 1H12H19C19.552 1 20 1.4477 20 2V16C20 16.5523 19.552 17 19 17H13V22C13 22.5523 12.552 23 12 23H6V21H11V17Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.q0u8copsv {
  fill-rule: evenodd;
  d: path("M12 10H5C4.448 10 4 10.4477 4 11V16C4 16.5523 4.448 17 5 17H19C19.552 17 20 16.5523 20 16V11C20 10.4477 19.552 10 19 10H12ZM13.5 6.5C13.5 7.3284 12.828 8 12 8C11.172 8 10.5 7.3284 10.5 6.5C10.5 5.6716 11.172 5 12 5C12.828 5 13.5 5.6716 13.5 6.5Z");
}

</style>
