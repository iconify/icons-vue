<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="zcql9i17h"/><path class="qrp-6-_jq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qrp-6-_jq {
  d: path("M133.66 106.34a8 8 0 0 0-11.32 0l-80 80A8 8 0 0 0 48 200h160a8 8 0 0 0 5.66-13.66ZM67.31 184L128 123.31L188.69 184ZM40 72a8 8 0 0 1 8-8h160a8 8 0 0 1 0 16H48a8 8 0 0 1-8-8");
}

.zcql9i17h {
  d: path("M208 192H48l80-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
