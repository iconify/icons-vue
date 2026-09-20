<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krh9v2bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-photo-alternate-outline-sharp" /></template>
<style>
.krh9v2bjr {
  fill: currentColor;
  d: path("M4 20V4h8.616v1H5v14h14v-7.615h1V20zm2.77-3.616h10.46L14 12.077l-3 3.789l-2-2.404zM17 9V7h-2V6h2V4h1v2h2v1h-2v2z");
}

</style>
