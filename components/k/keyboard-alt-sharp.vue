<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxtgqcbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-alt-sharp" /></template>
<style>
.wxtgqcbgw {
  fill: currentColor;
  d: path("M1 20V4h22v16zm7-3h8v-2H8zm-3-3.5h2v-2H5zm4 0h2v-2H9zm4 0h2v-2h-2zm4 0h2v-2h-2zM5 10h2V8H5zm4 0h2V8H9zm4 0h2V8h-2zm4 0h2V8h-2z");
}

</style>
