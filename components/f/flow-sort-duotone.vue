<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oknxkqvqx"/><path clip-rule="evenodd" class="a73s27brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-sort-duotone" /></template>
<style>
.a73s27brg {
  fill-rule: evenodd;
  d: path("M12 13L22 13C22.5522 13 22.9999 12.5524 23 12.0002C23.0001 11.0274 22.5291 10.043 21.59 9.456L13.59 4.456C12.6172 3.848 11.3828 3.848 10.41 4.456L2.41 9.456C1.4707 10.0429 1 11.0275 1 12C1 12.5523 1.4477 13 2 13Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.oknxkqvqx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.41 17.044L2.41 14.544C1.4708 13.957 1 12.9725 1 12C1 11.0275 1.4708 10.043 2.41 9.456L10.41 4.456C11.3828 3.848 12.6172 3.848 13.59 4.456L21.59 9.456C22.5292 10.043 23.0001 11.0275 23.0001 12C23.0001 12.9725 22.5292 13.957 21.59 14.544L13.59 19.544C12.6172 20.152 11.3828 20.152 10.41 19.544Z");
}

</style>
