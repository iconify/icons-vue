<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9g-o1bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-card" /></template>
<style>
.b9g-o1bsp {
  fill: currentColor;
  d: path("M4 12h16V8H4zm15 10v-3h-3v-2h3v-3h2v3h3v2h-3v3zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v6h-3q-2.075 0-3.537 1.463T14 17v3z");
}

</style>
