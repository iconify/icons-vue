<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk-vvwbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-outline-sharp" /></template>
<style>
.wk-vvwbwp {
  fill: currentColor;
  d: path("M2 19V5h20v14zm2-2h16V7H4zm4-1h8v-2H8zm-3-3h2v-2H5zm3 0h2v-2H8zm3 0h2v-2h-2zm3 0h2v-2h-2zm3 0h2v-2h-2zM5 10h2V8H5zm3 0h2V8H8zm3 0h2V8h-2zm3 0h2V8h-2zm3 0h2V8h-2zM4 17V7z");
}

</style>
