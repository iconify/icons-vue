<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfin2p7vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:insert-page-break-outline" /></template>
<style>
.rfin2p7vg {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20v-3h2v3h12v-3h2v3q0 .825-.587 1.413T18 22zM4 11V4q0-.825.588-1.412T6 2h8l6 6v3h-2V9h-5V4H6v7zm5 4v-2h6v2zm8 0v-2h6v2zM1 15v-2h6v2zm11 2");
}

</style>
