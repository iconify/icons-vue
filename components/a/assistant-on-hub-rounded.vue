<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i804_rd8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assistant-on-hub-rounded" /></template>
<style>
.i804_rd8a {
  fill: currentColor;
  d: path("M10.807 12.001q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23q-.23.23-.23.54t.23.539t.54.23t.539-.23m-3.46 0q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23q-.23.23-.23.54t.23.539t.54.23t.539-.23m6.386.23q.31 0 .539-.23t.23-.54t-.23-.539t-.54-.23t-.539.23q-.23.23-.23.54t.23.539t.54.23m3.999-.23q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.539.23t-.23.54t.23.539t.54.23t.539-.23M12 19.461q-2.436 0-3.968-.289q-1.532-.29-1.532-.745v-.965H4.616q-.691 0-1.153-.463T3 15.846V7.077q0-.69.463-1.153t1.152-.463h14.77q.69 0 1.152.463T21 7.077v8.77q0 .69-.463 1.152t-1.153.463H17.5v.965q0 .456-1.532.745q-1.532.29-3.968.29");
}

</style>
