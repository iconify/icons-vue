<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="xvqpnzzel"/><path class="rlpkcqz_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:device-mobile-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rlpkcqz_n {
  d: path("M176 16H80a24 24 0 0 0-24 24v176a24 24 0 0 0 24 24h96a24 24 0 0 0 24-24V40a24 24 0 0 0-24-24M72 64h112v128H72Zm8-32h96a8 8 0 0 1 8 8v8H72v-8a8 8 0 0 1 8-8m96 192H80a8 8 0 0 1-8-8v-8h112v8a8 8 0 0 1-8 8");
}

.xvqpnzzel {
  d: path("M192 56v144H64V56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
