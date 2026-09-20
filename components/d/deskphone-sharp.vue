<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buep7oj_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:deskphone-sharp" /></template>
<style>
.buep7oj_h {
  fill: currentColor;
  d: path("M17 19h2V5h-2zM6 14h2v-2H6zm0 3h2v-2H6zm0-6h8V7H6zm3 3h2v-2H9zm0 3h2v-2H9zm3-3h2v-2h-2zm0 3h2v-2h-2zm-9 3V4h12V3h6v18h-6v-1z");
}

</style>
