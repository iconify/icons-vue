<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bskkyvgxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-panel-close-outline-sharp" /></template>
<style>
.bskkyvgxv {
  fill: currentColor;
  d: path("m12 11.5l4-4H8zM5 19h14v-3H5zm0-5h14V5H5zm0 2v3zm-2 5V3h18v18z");
}

</style>
