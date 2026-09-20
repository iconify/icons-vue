<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_zl3-l6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:jamboard-kiosk-outline-sharp" /></template>
<style>
.h_zl3-l6h {
  fill: currentColor;
  d: path("M6 21v-2h5v-3H2V3h20v13h-9v3h5v2zm-2-7h16V5H4zm0 0V5z");
}

</style>
