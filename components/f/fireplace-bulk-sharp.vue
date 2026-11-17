<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u117u_bxe"/><path class="afohtpbfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fireplace-bulk-sharp" /></template>
<style>
.afohtpbfn {
  d: path("M3 4a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2h-1v16h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1V4Zm3 16h12V4H6Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u117u_bxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.981 6.304c.263 1.315 1.062 2.353 2.119 3.146a1 1 0 0 1 .107.093c1.209 1.21 1.543 2.802 1.543 4.457a4.74 4.74 0 0 1-1.391 3.359A4.75 4.75 0 0 1 7.25 14c0-.92.25-1.914.918-2.582a.999.999 0 0 1 1.707.707a.25.25 0 1 0 .5 0c0-.187-.015-.38-.075-.558c-.056-.165-.146-.32-.23-.471a9 9 0 0 1-.214-.399c-.417-.833-.536-1.723-.256-2.62c.301-.962 1.003-1.739 1.775-2.358a1 1 0 0 1 1.606.585");
}

</style>
