<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_h7xqgow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-cafe-sharp" /></template>
<style>
.h_h7xqgow {
  fill: currentColor;
  d: path("M5 20v-1h14v1zm0-3.77V4h16v5.5h-3.692v6.73zM17.308 8.5H20V5h-2.692z");
}

</style>
