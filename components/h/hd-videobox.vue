<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="fk8n8bc7i"/><path class="h4gic8xte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hd-videobox" /></template>
<style>
.fk8n8bc7i {
  d: path("M28.617 26.835v9.943l8.615-4.974v-9.886zm-15.741 6.038l.033-9.976zm4.214 2.466l.033-9.976zm-1.26-22.366l9.714 5.652l3.4-7.64z");
}

.h4gic8xte {
  d: path("M41.753 13.724L23.998 24.062m.008 20.438l17.757-10.311l-.012-20.465L24.002 3.5L6.245 13.773l-.003 20.431zm0 0l-.004-20.439L6.236 13.773");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
