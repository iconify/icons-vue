<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="aim3b90ep"/><path class="ebon3_bsc"/><path class="mnd1yj6-n"/><path class="vyn3247hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cigarette" /></template>
<style>
.aim3b90ep {
  fill: var(--svg-color--f2b200, #f2b200);
  d: path("M0 50h26v14H0z");
}

.ebon3_bsc {
  fill: var(--svg-color--dce5e5, #dce5e5);
  d: path("M26 50h34v14H26z");
}

.mnd1yj6-n {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M60 50h4v14h-4z");
}

.vyn3247hv {
  fill: var(--svg-color--abc2c6, #abc2c6);
  d: path("M33.5 16C28.4 35.1 43.9 9 64 47C53.3 32.9 18.8 43.2 4.3 27.5C-15.8 5.8 41.9-15.6 33.5 16");
}

</style>
