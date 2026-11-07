<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rmno26bgf"/><path class="n2duo29hr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n2duo29hr {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414M16.296 9.29l3.28-3.28a.999.999 0 1 1 1.414 1.414l-3.281 3.282h-.001v.001h-.001l-.001.001l-.001.001l-.014.014l-1.368 1.357l-1.415-1.414l1.376-1.364l.006-.006l.002-.002l.001-.001v-.001Z");
}

.rmno26bgf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.475 17.233L8.243 4H17a5 5 0 0 1 5 5v6a5 5 0 0 1-.525 2.233M4.608 4.608l14.784 14.784c-.734.4-1.556.608-2.392.608H7a5 5 0 0 1-5-5V9c0-1.832.998-3.517 2.608-4.392");
}

</style>
