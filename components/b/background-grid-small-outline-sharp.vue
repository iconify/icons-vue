<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-01u3btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:background-grid-small-outline-sharp" /></template>
<style>
.d-01u3btk {
  fill: currentColor;
  d: path("M5 19h2v-2H5zm4 0h2v-2H9zm4 0h2v-2h-2zm4 0h2v-2h-2zM5 7h2V5H5zm0 4h2V9H5zm0 4h2v-2H5zm4-8h2V5H9zm0 4h2V9H9zm0 4h2v-2H9zm4-8h2V5h-2zm0 4h2V9h-2zm0 4h2v-2h-2zm4-8h2V5h-2zm0 4h2V9h-2zm0 4h2v-2h-2zM3 21V3h18v18z");
}

</style>
