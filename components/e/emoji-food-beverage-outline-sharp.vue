<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyhuex28v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emoji-food-beverage-outline-sharp" /></template>
<style>
.eyhuex28v {
  fill: currentColor;
  d: path("M5 20v-1h14v1zm0-3.77V4h14.308q.69 0 1.191.472T21 5.634v2.231q0 .69-.501 1.163q-.501.472-1.191.472h-2v6.73zM6 5h10.308zm11.308 3.5h2q.288 0 .49-.183T20 7.865v-2.23q0-.27-.202-.452Q19.596 5 19.308 5h-2zm-1 6.73V5H9.885v1.17l1.73 1.426v3.75h-4.23v-3.75l1.73-1.427V5H6v10.23zM9.116 5h.769z");
}

</style>
