<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i1z-n_j1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:familyalbum" /></template>
<style>
.i1z-n_j1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4 21.366v14.28l9.92-9.08l10.08 9.2l10.08-9.16l9.92 8.96v-14.28l-9.93-8.91l-10.013 9.163l-10.126-9.305zm9.93-9.132l-.01 14.332m10.137-5.026L24 35.767m10.07-23.393l.01 14.231");
}

</style>
