<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x37weabng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fact-check-outline-sharp" /></template>
<style>
.x37weabng {
  fill: currentColor;
  d: path("M5 17h5v-2H5zm9.55-2l4.95-4.95l-1.425-1.425l-3.525 3.55l-1.425-1.425l-1.4 1.425zM5 13h5v-2H5zm0-4h5V7H5zM2 21V3h20v18zm2-2h16V5H4zm0 0V5z");
}

</style>
