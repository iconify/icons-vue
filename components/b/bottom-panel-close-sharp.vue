<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_p9qs36a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-panel-close-sharp" /></template>
<style>
.h_p9qs36a {
  fill: currentColor;
  d: path("m12 11.5l4-4H8zM5 14h14V5H5zm-2 7V3h18v18z");
}

</style>
