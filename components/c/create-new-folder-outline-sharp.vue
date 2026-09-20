<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgn1i_ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:create-new-folder-outline-sharp" /></template>
<style>
.hgn1i_ber {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm2-2h16V8h-8.825l-2-2H4zm0 0V6zm10-2h2v-2h2v-2h-2v-2h-2v2h-2v2h2z");
}

</style>
