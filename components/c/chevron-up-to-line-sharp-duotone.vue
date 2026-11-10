<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l-olbdpdo"/><path class="p29r_ojqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-up-to-line-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l-olbdpdo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.315 10.27C11.708 9.95 12.343 9.93 12.707 10.29L19 16.59L17.586 18L12 12.41L6.414 18L4.999 16.58L11.315 10.27ZM20 6V8H4V6H20Z");
}

.p29r_ojqj {
  d: path("M11.312 10.27C11.704 9.96 12.344 9.93 12.708 10.29L19.001 16.59L17.587 18L12.001 12.41L6.415 18L5 16.58L11.312 10.27Z");
}

</style>
