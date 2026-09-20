<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a6rpb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-mac-outline-sharp" /></template>
<style>
.n0a6rpb_d {
  fill: currentColor;
  d: path("M8 21v-1l2-2H2V3h20v15h-8l2 2v1zm-4-8h16V5H4zm0 0V5z");
}

</style>
