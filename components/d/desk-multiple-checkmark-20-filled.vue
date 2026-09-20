<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y33nwsqul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-checkmark-20-filled" /></template>
<style>
.y33nwsqul {
  fill: currentColor;
  d: path("M9 15a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-5h7zm7 1.5a.5.5 0 0 1-1 0v-5.524a5.5 5.5 0 0 0 1-.185zm1.998-2a.5.5 0 1 1-1 0v-4.1a5.5 5.5 0 0 0 1-.656zM4.5 11.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM14.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.023 6a5.47 5.47 0 0 0 1.235 3H2V8a2 2 0 0 1 2-2zm7.83-2.354a.5.5 0 0 0-.707 0L13.5 6.293l-.646-.647a.5.5 0 1 0-.707.708l1 1a.5.5 0 0 0 .707 0l3-3a.5.5 0 0 0 0-.708M9.209 4a5.5 5.5 0 0 0-.185 1H4.266a2 2 0 0 1 1.732-1z");
}

</style>
