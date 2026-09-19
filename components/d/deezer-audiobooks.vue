<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jd6nxbc0l"/><path class="xnzzp_bza"/><path class="cu8rhsjbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deezer-audiobooks" /></template>
<style>
.cu8rhsjbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.133 19.24l7.892-2.27l6.474 22.51l-7.89 2.27zm.001 8.65l-16.423-9.482v18.963z");
}

.jd6nxbc0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 6.25h8.211v35.5H4.5z");
}

.xnzzp_bza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.923 32.63v9.12h-8.212V6.25h8.212v16.899m0 0v-9.12h8.211V41.75h-8.211v-9.12");
}

</style>
