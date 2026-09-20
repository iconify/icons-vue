<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl45xv2cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-lock-sharp" /></template>
<style>
.tl45xv2cz {
  fill: currentColor;
  d: path("m12 13l8-5V6l-8 5l-8-5v2zM2 20V4h20v6h-1q-2.075 0-3.537 1.463T16 15v5zm16 0v-5h1v-1q0-.825.588-1.412T21 12t1.413.588T23 14v1h1v5zm2-5h2v-1q0-.425-.288-.712T21 13t-.712.288T20 14z");
}

</style>
