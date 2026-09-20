<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="epmiu-b_h"/><path class="o6ow82zeu"/><path class="zw66s8b1o"/><path class="rfpc8ubdp"/><path class="t-mha0g5h"/><path class="z0j9wnbwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-clone-duotone-bold" /></template>
<style>
.epmiu-b_h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o6ow82zeu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.19 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rfpc8ubdp {
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t-mha0g5h {
  d: path("M19.19 8.37a4 4 0 1 1 -3.38 0");
}

.z0j9wnbwo {
  d: path("M4 19.5h16");
}

.zw66s8b1o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 19.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
