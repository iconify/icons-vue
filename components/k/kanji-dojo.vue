<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zzetzpblz"/><path class="llztq_cgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kanji-dojo" /></template>
<style>
.llztq_cgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.099 28.34H41.9M13.848 16.07h19.419c1.186 0 1.402 1.013.656 1.837c-2.922 3.232-6.866 4.687-10.306 5.49c-1.006.235-.818.802-.374 1.265c.978 1.02 2.064 2.448 2.064 5.002v8.928c0 2.17-1.614 3.444-3.556 3.444c-1.734 0-3.23-.365-5.203-1.376m7.46-35.654v4.063M7.02 15.844v-5.181A1.59 1.59 0 0 1 8.608 9.07H39.41c.878 0 1.59.711 1.59 1.59v5.127");
}

.zzetzpblz {
  cx: 38.821px;
  cy: 39.995px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

</style>
