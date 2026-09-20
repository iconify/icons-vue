<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bw1pvkb1e"/><path class="slorjqbuy"/><path class="rd9culn5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:lock-closed" /></template>
<style>
.bw1pvkb1e {
  d: path("M8 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2.5 0a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.rd9culn5u {
  d: path("M14 4a4 4 0 0 0-8 0v5h8zm-2 0v3H8V4a2 2 0 1 1 4 0");
}

.slorjqbuy {
  d: path("M13 7H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-4a4 4 0 0 0-4-4m-8 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2z");
}

</style>
