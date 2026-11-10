<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qnlhdibuj"/><path class="pel7kz6rk"/><path class="c0zau_t-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-image-sharp-duotone" /></template>
<style>
.c0zau_t-d {
  d: path("M13.5 10C14.328 10 15 10.67 15 11.5C15 12.33 14.328 13 13.5 13C12.672 13 12 12.33 12 11.5C12 10.67 12.672 10 13.5 10Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pel7kz6rk {
  d: path("M13.092 16.06L17.093 13.06L20 15.96V20H4V16.96L9 11.96L13.092 16.06Z");
}

.qnlhdibuj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 6C21.552 6 22 6.45 22 7V21C22 21.55 21.552 22 21 22H3C2.448 22 2 21.55 2 21V7C2 6.45 2.448 6 3 6H21ZM20 2V4H4V2H20Z");
}

</style>
