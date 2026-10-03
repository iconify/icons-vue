<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="t_rqxn3wm"/><path class="s0f2z-92o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks-2-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s0f2z-92o {
  d: path("M7 2C7 1.4477 7.4477 1 8 1L16 1C16.5523 1 17 1.4477 17 2L17 10C17 10.5523 16.5523 11 16 11L8 11C7.4477 11 7 10.5523 7 10L7 2Z");
}

.t_rqxn3wm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M1 14C1 13.4477 1.4477 13 2 13L10 13C10.5523 13 11 13.4477 11 14L11 22C11 22.5523 10.5523 23 10 23L2 23C1.4477 23 1 22.5523 1 22L1 14ZM13 14C13 13.4477 13.4477 13 14 13L22 13C22.5523 13 23 13.4477 23 14L23 22C23 22.5523 22.5523 23 22 23L14 23C13.4477 23 13 22.5523 13 22L13 14Z");
}

</style>
