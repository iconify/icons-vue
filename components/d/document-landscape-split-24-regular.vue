<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txdppcf2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-landscape-split-24-regular" /></template>
<style>
.txdppcf2i {
  fill: currentColor;
  d: path("M3.5 6a.5.5 0 0 1 .5-.5h6.5v13H4a.5.5 0 0 1-.5-.5zM12 18.5v-13h2V10a2 2 0 0 0 2 2h4.5v6a.5.5 0 0 1-.5.5zm3.5-11.878l3.879 3.878H16a.5.5 0 0 1-.5-.5zm5.914 3.793l-5.828-5.829A2 2 0 0 0 14.172 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-6.172a2.05 2.05 0 0 0-.586-1.413");
}

</style>
