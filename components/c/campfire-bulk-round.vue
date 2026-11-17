<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mto5fmbov"/><path class="wouu8-nbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:campfire-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mto5fmbov {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.981 2.804c.263 1.315 1.062 2.353 2.119 3.146a1 1 0 0 1 .107.093c1.209 1.21 1.543 2.802 1.543 4.457a4.74 4.74 0 0 1-1.391 3.359A4.75 4.75 0 0 1 7.25 10.5c0-.92.25-1.914.918-2.582a.999.999 0 0 1 1.707.707c0 .101.06.193.154.232a.25.25 0 0 0 .346-.232c0-.187-.015-.38-.075-.558c-.056-.165-.146-.32-.23-.471a9 9 0 0 1-.214-.399c-.417-.833-.536-1.723-.256-2.62c.301-.962 1.003-1.739 1.775-2.358a1 1 0 0 1 1.606.585");
}

.wouu8-nbr {
  d: path("M4.243 16.03L12 17.969l7.757-1.939a1 1 0 0 1 .486 1.94L16.123 19l4.12 1.03a1 1 0 0 1-.486 1.94L12 20.031L4.243 21.97a1 1 0 0 1-.486-1.94L7.877 19l-4.12-1.03a1 1 0 0 1 .486-1.94");
}

</style>
