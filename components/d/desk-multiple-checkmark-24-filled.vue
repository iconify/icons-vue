<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku73tpbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-checkmark-24-filled" /></template>
<style>
.ku73tpbrb {
  fill: currentColor;
  d: path("M11 18.75A2.25 2.25 0 0 1 8.75 21h-4.5A2.25 2.25 0 0 1 2 18.75V12h9zm8.5 1.5a.75.75 0 0 1-1.5 0v-7.271a6.5 6.5 0 0 0 1.5-.294zm2.501-2.5a.75.75 0 0 1-1.499.036v-5.521a6.5 6.5 0 0 0 1.499-1.078zM5.25 14a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zM17.5 1a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-6.478 6a6.46 6.46 0 0 0 1.357 3.5H2V9.25A2.25 2.25 0 0 1 4.25 7zm9.832-2.854a.5.5 0 0 0-.707 0L16.5 7.793l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.708m-9.54.354q-.233.719-.293 1.5H4.629A2.25 2.25 0 0 1 6.75 4.5z");
}

</style>
