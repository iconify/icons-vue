<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w35l7wb0k"/><path class="wyaixbcry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bone-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w35l7wb0k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 10l-7 7c-.427.427-.342.802-.159 1.315c.078.221.159.448.159.685a2 2 0 1 1-4 0a1 1 0 0 0-1-1a2 2 0 1 1 0-4c.237 0 .464.081.685.159c.513.183.888.268 1.315-.159l7-7c.427-.427.342-.802.159-1.315C14.081 5.464 14 5.237 14 5a2 2 0 1 1 4 0a1 1 0 0 0 1 1a2 2 0 1 1 0 4c-.237 0-.464-.081-.685-.159c-.513-.183-.888-.268-1.315.159");
}

.wyaixbcry {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 10c.7-.7 1.3 0 2 0a2 2 0 1 0 0-4a1 1 0 0 1-1-1a2 2 0 1 0-4 0c0 .7.7 1.3 0 2l-7 7c-.7.7-1.3 0-2 0a2 2 0 1 0 0 4a1 1 0 0 1 1 1a2 2 0 1 0 4 0c0-.7-.7-1.3 0-2Z");
}

</style>
