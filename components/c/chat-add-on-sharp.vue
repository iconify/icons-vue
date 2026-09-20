<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm-k1s_pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-add-on-sharp" /></template>
<style>
.zm-k1s_pf {
  fill: currentColor;
  d: path("M7 9h8V7H7zm0 4h5v-2H7zm10 7v-3h-3v-2h3v-3h2v3h3v2h-3v3zM3 20V3h16v7.075q-.25-.05-.5-.062T18 10q-2.525 0-4.262 1.75T12 16q0 .25.013.5t.062.5H6z");
}

</style>
