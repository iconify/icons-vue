<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="myjifbbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bibleproject" /></template>
<style>
.myjifbbpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.661 5.5v31.411l8.414-2.89V42.5l10.178-10.177l18.086 4.524V5.5l-18.202 4.981z");
}

</style>
