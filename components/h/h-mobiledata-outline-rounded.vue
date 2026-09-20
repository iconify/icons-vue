<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg9ol5b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:h-mobiledata-outline-rounded" /></template>
<style>
.qg9ol5b6o {
  fill: currentColor;
  d: path("M9 13v3q0 .425-.288.713T8 17t-.712-.288T7 16V8q0-.425.288-.712T8 7t.713.288T9 8v3h6V8q0-.425.288-.712T16 7t.713.288T17 8v8q0 .425-.288.713T16 17t-.712-.288T15 16v-3z");
}

</style>
