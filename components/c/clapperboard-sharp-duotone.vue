<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u895eh18x"/><path class="k6_l4cblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clapperboard-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k6_l4cblx {
  d: path("M9.977 2L12 2L12.3229 2L12.0715 2.6286L10.3229 7L7.9771 7L9.4285 3.3714ZM14.477 2L16.8229 2L16.5715 2.6286L14.8229 7L12.4771 7L13.9285 3.3714ZM18.977 2L21 2C21.5523 2 22 2.4477 22 3L22 7L16.9771 7L18.4285 3.3714ZM5.8229 7L2 7L2 3C2 2.4477 2.4477 2 3 2L7.8229 2L7.5715 2.6286Z");
}

.u895eh18x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 9Z");
}

</style>
