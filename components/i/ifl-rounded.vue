<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igfgexren"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ifl-rounded" /></template>
<style>
.igfgexren {
  fill: currentColor;
  d: path("M16.774 16.774q.38-.38.38-.928t-.38-.928t-.928-.38t-.928.38t-.38.928t.38.928t.928.38t.928-.38m-3.846-3.846q.38-.38.38-.928t-.38-.928t-.928-.38t-.928.38t-.38.928t.38.928t.928.38t.928-.38M9.082 9.082q.38-.38.38-.928t-.38-.928t-.928-.38t-.928.38t-.38.928t.38.928t.928.38t.928-.38M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
