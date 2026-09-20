<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmzes4bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hardware" /></template>
<style>
.jmzes4bih {
  fill: currentColor;
  d: path("M9 11V8H4q0-2.075 1.463-3.537T9 3h6v3l3-3h2v8h-2l-3-3v3zm1 10q-.425 0-.712-.288T9 20v-7h6v7q0 .425-.288.713T14 21z");
}

</style>
