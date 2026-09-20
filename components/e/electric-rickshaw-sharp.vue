<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn54twz_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:electric-rickshaw-sharp" /></template>
<style>
.vn54twz_q {
  fill: currentColor;
  d: path("M6.192 16.616q-1.013 0-1.708-.64t-.861-1.514H2.308V4h13.756l4.167 5.423v2.227q.644.3 1.053.905T21.692 14q0 1.077-.769 1.846t-1.846.77q-1.014 0-1.705-.63t-.876-1.525H8.773q-.177.875-.862 1.515q-.686.64-1.719.64M3.308 8.5h4.5V5h-4.5zm5.5 5.039h5.961V5H8.808v3.5h3.5v1h-3.5zM15.769 9.5h3.246L15.77 5.254zm-8.431 5.645q.47-.47.47-1.145t-.47-1.145t-1.146-.47t-1.145.47T4.577 14t.47 1.145t1.145.47t1.146-.47m12.884 0q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47m-7.068 7.509l-5.115-2.577h3.384v-1.73l5.116 2.576h-3.385z");
}

</style>
