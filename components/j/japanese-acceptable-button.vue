<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uwtnf60nf"/><path class="qzip-ablg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:japanese-acceptable-button" /></template>
<style>
.qzip-ablg {
  fill: currentColor;
  d: path("M32 2C15.473 2 2 15.474 2 32c0 16.527 13.473 30 30 30c16.523 0 30-13.473 30-30C62 15.474 48.523 2 32 2m-8.361 38.822V43.5H19v-17h16v14.322zM48 22.857h-3.59v21.264c0 2.658-.547 4.143-2.393 4.957c-1.794.82-4.484.922-8.273.922c-.201-1.482-1.047-3.73-1.744-5.113c2.592.156 5.432.156 6.23.104c.797-.049 1.096-.256 1.096-.971V22.857H16V18h32z");
}

.uwtnf60nf {
  fill: currentColor;
  d: path("M23.639 30.932h6.418v5.461h-6.418z");
}

</style>
