<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l6fbk-bit"/><path class="atgrwwbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-5-sharp-duotone" /></template>
<style>
.atgrwwbwn {
  d: path("M7.25 5.75C8.0784 5.75 8.75 6.4216 8.75 7.25C8.75 8.0784 8.0784 8.75 7.25 8.75C6.4216 8.75 5.75 8.0784 5.75 7.25C5.75 6.4216 6.4216 5.75 7.25 5.75ZM16.75 5.75C17.5784 5.75 18.25 6.4216 18.25 7.25C18.25 8.0784 17.5784 8.75 16.75 8.75C15.9216 8.75 15.25 8.0784 15.25 7.25C15.25 6.4216 15.9216 5.75 16.75 5.75ZM12 10.5C12.8284 10.5 13.5 11.1716 13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5ZM7.25 15.25C8.0784 15.25 8.75 15.9216 8.75 16.75C8.75 17.5784 8.0784 18.25 7.25 18.25C6.4216 18.25 5.75 17.5784 5.75 16.75C5.75 15.9216 6.4216 15.25 7.25 15.25ZM16.75 15.25C17.5784 15.25 18.25 15.9216 18.25 16.75C18.25 17.5784 17.5784 18.25 16.75 18.25C15.9216 18.25 15.25 17.5784 15.25 16.75C15.25 15.9216 15.9216 15.25 16.75 15.25Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l6fbk-bit {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2Z");
}

</style>
