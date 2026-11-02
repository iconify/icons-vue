<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ek5rg2emf"/><path class="xtjxpq98z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handshake-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ek5rg2emf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4h6.605c1.614-1.418 3.827-1.916 5.92-1.53c.667.12 1.315.334 1.922.636L19.236 4H21a1 1 0 0 1 1 1v7c0 .265-.105.52-.293.707l-1.409 1.409a3.121 3.121 0 0 1-4.944 3.65a3.123 3.123 0 0 1-5 1a3.12 3.12 0 0 1-5.061.941l-3-3A1 1 0 0 1 2 16V5a1 1 0 0 1 1-1");
}

.xtjxpq98z {
  d: path("M4 5v10.586l2.707 2.707c.213.213.492.328.793.328a1.119 1.119 0 0 0 .793-1.914a.999.999 0 1 1 1.414-1.414l2 2a1.121 1.121 0 0 0 1.586-1.585l-1-1.001a.999.999 0 1 1 1.414-1.414l3 3a1.121 1.121 0 1 0 1.586-1.586l-.869-.869l-.001-.001l-3.13-3.13a1.83 1.83 0 0 0-2.586 0l-1 1a3.12 3.12 0 0 1-5.222-1.399a3.12 3.12 0 0 1 .808-3.015l3-3a.999.999 0 1 1 1.414 1.414l-3 3a1.121 1.121 0 1 0 1.586 1.586l1-1a3.83 3.83 0 0 1 5.414 0L19 12.586l1-1V5a1 1 0 0 1 2 0v7c0 .265-.105.52-.293.707l-1.409 1.409a3.121 3.121 0 0 1-4.944 3.65a3.124 3.124 0 0 1-5 1a3.125 3.125 0 0 1-5.061.941l-3-3A1 1 0 0 1 2 16V5a1 1 0 0 1 2 0");
}

</style>
