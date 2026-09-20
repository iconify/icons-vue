<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="e84lw4bzo"/><path class="ri_favbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-post-outline-bold" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.e84lw4bzo {
  d: path("M12 10v5.5");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.ri_favbdz {
  d: path("M9.5 12.5 12 10l2.5 2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
