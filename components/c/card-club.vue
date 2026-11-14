<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzd2zz9tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:card-club" /></template>
<style>
.lzd2zz9tr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75H8q-1.76 0-3.005 1.245T3.75 6v12q0 1.76 1.245 3.005T8 22.25h8q1.76 0 3.005-1.245T20.25 18V6q0-1.76-1.245-3.005T16 1.75M9.765 16.853l.331-1.658q-1.188.379-2.302-.209q-1.151-.608-1.493-1.864q-.342-1.255.34-2.363q.683-1.108 1.958-1.366q.224-.046.442-.06q-.031-.194-.039-.399q-.047-1.274.838-2.193q.885-.918 2.16-.918t2.16.918q.885.919.838 2.193q-.008.205-.039.399q.218.014.442.06q1.275.258 1.958 1.366q.682 1.108.34 2.363q-.342 1.256-1.493 1.864q-1.114.588-2.302.209l.331 1.658q.015.072.015.146t-.014.147q-.015.072-.043.14t-.069.13t-.093.114t-.114.093t-.129.07q-.068.028-.141.042t-.147.015h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.75 17t.015-.147");
}

</style>
