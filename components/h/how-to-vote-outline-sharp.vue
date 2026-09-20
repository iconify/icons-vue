<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxno5qx2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:how-to-vote-outline-sharp" /></template>
<style>
.vxno5qx2p {
  fill: currentColor;
  d: path("M3 22v-6.55l2.75-3.125l1.425 1.425l-2 2.25h13.65l-1.95-2.2l1.425-1.425L21 15.45V22zm2-2h14v-2H5zm7.05-4.2L5.7 9.45l7.775-7.775l6.35 6.35zm0-2.825L17 8.025L13.475 4.5l-4.95 4.95zM5 20v-2z");
}

</style>
