<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pbia6yb8w"/><path clip-rule="evenodd" class="c1ra23j4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alt-two-tone" /></template>
<style>
.c1ra23j4c {
  fill-rule: evenodd;
  d: path("M21 20C21.5523 20 22 20.448 22 21C22 21.552 21.5523 22 21 22H13C12.4477 22 12 21.552 12 21C12 20.448 12.4477 20 13 20H21Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pbia6yb8w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 2C21.5523 2 22 2.448 22 3C22 3.552 21.5523 4 21 4H17.2998C16.9047 4 16.5462 4.233 16.3857 4.594L9.4414 20.219C8.9598 21.302 7.8856 22 6.7002 22H3C2.4477 22 2 21.552 2 21C2 20.448 2.4477 20 3 20H6.7002C7.0953 20 7.4538 19.767 7.6143 19.406L14.5586 3.781C15.0402 2.698 16.1144 2 17.2998 2H21Z");
}

</style>
