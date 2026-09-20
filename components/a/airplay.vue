<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyfzy5btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airplay" /></template>
<style>
.dyfzy5btc {
  fill: currentColor;
  d: path("M7.423 20L12 15.423L16.577 20zm-2.807-2q-.672 0-1.144-.472T3 16.385V5.615q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v10.769q0 .67-.472 1.143q-.472.472-1.143.472H18l-6-6l-6 6z");
}

</style>
