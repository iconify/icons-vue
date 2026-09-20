<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbv9g9brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hand-package-outline-sharp" /></template>
<style>
.xbv9g9brb {
  fill: currentColor;
  d: path("M15 4H9v7h6zm5 0h-3v7h3zm-5.625 9H8v6h6.6l5-4.125q-.2-.2-.45-.3t-.525-.15q-.425-.075-.825.025t-.75.375L14.35 17H10v-2h3.65l1.1-.9q.125-.075.188-.2t.062-.275q0-.25-.187-.437T14.375 13M6 13H4v7h2zm1 0V2h15v11zm.725 9H2V11h12.375q2.125 0 4.1.725t3.175 2.45l.675 1.025l-6.95 5.8h-7.65z");
}

</style>
