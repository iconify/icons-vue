<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rjexhybae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ietisalat" /></template>
<style>
.rjexhybae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.261 7.117c0 1.445-1.253 2.617-2.798 2.617h0c-1.545 0-2.798-1.172-2.798-2.617h0c0-1.445 1.253-2.617 2.798-2.617h0c1.545 0 2.798 1.172 2.798 2.617M15.679 43.5c7.893-5.301 15.918-12.717 13.93-26.194c-.46-3.118-4.63-4.216-6.231 0c-1.558 4.099-2.286 17.109 2.413 23.29c1.717 2.259 4.75 1.728 6.53-.615");
}

</style>
