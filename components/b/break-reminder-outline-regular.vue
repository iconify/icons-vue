<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r57e8zbzz"/><path class="ng_tlibuk"/><path class="s0v-_1bji"/><path class="v9hia4w8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:break-reminder-outline-regular" /></template>
<style>
.ng_tlibuk {
  d: path("M15 9a3 3 0 0 1 0 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r57e8zbzz {
  d: path("M4 9v9h11V9");
}

.s0v-_1bji {
  d: path("M7 3a3 3 0 0 1 0 6");
}

.v9hia4w8h {
  d: path("M12 3a3 3 0 0 1 0 6");
}

</style>
