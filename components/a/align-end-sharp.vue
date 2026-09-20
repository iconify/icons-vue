<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmdtxac7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-end-sharp" /></template>
<style>
.fmdtxac7y {
  fill: currentColor;
  d: path("M3 21v-1h18v1zm4.5-10.5v-2h9v2zm0 6v-2h9v2z");
}

</style>
