<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u--hs3bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kanjitree" /></template>
<style>
.u--hs3bfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5v37M6.704 16.092h34.592m-17.296 0c0 4.964-12.925 16.087-17.24 18.88M24 16.092c0 4.964 12.925 16.087 17.24 18.88");
}

</style>
