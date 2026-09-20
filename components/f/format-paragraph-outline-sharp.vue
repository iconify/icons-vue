<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqe9pyrdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-paragraph-outline-sharp" /></template>
<style>
.qqe9pyrdv {
  fill: currentColor;
  d: path("M9 20v-6q-2.075 0-3.537-1.463T4 9t1.463-3.537T9 4h9v2h-2v14h-2V6h-3v14z");
}

</style>
