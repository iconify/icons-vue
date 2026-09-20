<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="il2jkacpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-20-regular" /></template>
<style>
.il2jkacpv {
  fill: currentColor;
  d: path("m13.354 10.854l-3 3a.5.5 0 0 1-.708 0l-3-3a.5.5 0 0 1 .708-.708L9.5 12.293V6.5a.5.5 0 0 1 1 0v5.793l2.146-2.147a.5.5 0 0 1 .708.708M10 18a8 8 0 1 0 0-16a8 8 0 0 0 0 16m7-8a7 7 0 1 1-14 0a7 7 0 0 1 14 0");
}

</style>
