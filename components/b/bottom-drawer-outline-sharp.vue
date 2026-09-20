<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffblv3a4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-drawer-outline-sharp" /></template>
<style>
.ffblv3a4h {
  fill: currentColor;
  d: path("M3 21V3h18v18zM5 5v8.25L6.25 12h11.5L19 13.25V5zm0 14h14v-3l-2-2H7l-2 2zm0 0h14z");
}

</style>
