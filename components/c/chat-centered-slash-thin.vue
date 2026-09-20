<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u1bv9ob4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-centered-slash-thin" /></template>
<style>
.u1bv9ob4a {
  fill: currentColor;
  d: path("M51 37.31a4 4 0 0 0-6 5.38L46.23 44H40a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h62.75l14.83 26a12 12 0 0 0 20.84 0l14.83-26h31.16L205 218.69a4 4 0 1 0 5.92-5.38ZM150.93 188a4 4 0 0 0-3.47 2l-16 28a4 4 0 0 1-6.94 0l-16-28a4 4 0 0 0-3.47-2H40a4 4 0 0 1-4-4V56a4 4 0 0 1 4-4h13.5l123.64 136ZM228 56v130a4 4 0 0 1-8 0V56a4 4 0 0 0-4-4H98.52a4 4 0 1 1 0-8H216a12 12 0 0 1 12 12");
}

</style>
