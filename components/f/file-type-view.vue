<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aysbslbjn"/><path class="lx1wo8brb"/><path class="i3_lixzcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-view" /></template>
<style>
.aysbslbjn {
  fill: var(--svg-color--e44f26, #e44f26);
  d: path("M5.902 27.201L3.655 2h24.69l-2.25 25.197L15.985 30z");
}

.i3_lixzcg {
  fill: var(--svg-color--fff, #fff);
  d: path("m15 20.681l-8-4.809v-1.743l8-4.81v2.697L9.897 15L15 17.986zm2-.003v-2.694L22.14 15L17 12.017V9.322l8 4.787v1.782z");
}

.lx1wo8brb {
  fill: var(--svg-color--f1662a, #f1662a);
  d: path("m16 27.858l8.17-2.265l1.922-21.532H16z");
}

</style>
