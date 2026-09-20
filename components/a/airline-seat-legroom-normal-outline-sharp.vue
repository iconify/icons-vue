<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4vrpkbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-legroom-normal-outline-sharp" /></template>
<style>
.x4vrpkbut {
  fill: currentColor;
  d: path("M16 21v-7H6V3h6v6h7v9h3v3zm-2-4H3V3h2v12h9z");
}

</style>
