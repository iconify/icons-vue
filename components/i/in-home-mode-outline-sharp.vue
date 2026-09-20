<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6dhdbclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:in-home-mode-outline-sharp" /></template>
<style>
.k6dhdbclo {
  fill: currentColor;
  d: path("M4 20v-9.375L2.2 12l-1.175-1.575L12 2l11 8.4l-1.2 1.6L12 4.5L6 9.1V18h3v2zm10.925 2L10.7 17.75l1.4-1.425l2.825 2.825L20.6 13.5l1.4 1.425z");
}

</style>
