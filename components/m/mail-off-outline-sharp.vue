<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqjx53bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-off-outline-sharp" /></template>
<style>
.xqjx53bzz {
  fill: currentColor;
  d: path("M20.429 21.856L17.573 19H3V5h2l1 1H4v12h12.573L2.606 4.033l.713-.714l17.823 17.823zM21 18.188l-1-1V6.886l-6.221 4.082l-.687-.686L19.692 6H8.812l-1-1H21z");
}

</style>
