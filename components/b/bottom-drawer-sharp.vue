<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_dgj4b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-drawer-sharp" /></template>
<style>
.i_dgj4b5t {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 5v8.25L6.25 12h11.5L19 13.25V5z");
}

</style>
