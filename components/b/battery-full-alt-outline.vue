<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vktrr_tvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-full-alt-outline" /></template>
<style>
.vktrr_tvc {
  fill: currentColor;
  d: path("M5 17q-.425 0-.712-.288T4 16v-2H2v-4h2V8q0-.425.288-.712T5 7h16q.425 0 .713.288T22 8v8q0 .425-.288.713T21 17z");
}

</style>
