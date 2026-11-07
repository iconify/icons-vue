<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b6advrghy"/><path class="v91-pwkuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-duotone-sharp" /></template>
<style>
.b6advrghy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7 17l-4 4V3h1l14 14Zm3-14h11v11Z");
}

.ft5dv1b6b {
  fill: none;
}

.v91-pwkuq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7l-4 4V2m7 1h11v11m-3 3h-6M3 2l19 19");
}

</style>
