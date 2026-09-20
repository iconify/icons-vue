<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f07l2kbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-onscreen-sharp" /></template>
<style>
.f07l2kbsv {
  fill: currentColor;
  d: path("M8 17h8v-2H8zm-3-3h2v-2H5zm3 0h2v-2H8zm3 0h2v-2h-2zm3 0h2v-2h-2zm3 0h2v-2h-2zM2 20V4h20v16zM4 9h16V6H4z");
}

</style>
