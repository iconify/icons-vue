<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4u55z06y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-sharp" /></template>
<style>
.o4u55z06y {
  fill: currentColor;
  d: path("M2 19V5h20v14zm6-3h8v-2H8zm-3-3h2v-2H5zm3 0h2v-2H8zm3 0h2v-2h-2zm3 0h2v-2h-2zm3 0h2v-2h-2zM5 10h2V8H5zm3 0h2V8H8zm3 0h2V8h-2zm3 0h2V8h-2zm3 0h2V8h-2z");
}

</style>
