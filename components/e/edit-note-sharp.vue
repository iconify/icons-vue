<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qytj3oddg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-note-sharp" /></template>
<style>
.qytj3oddg {
  fill: currentColor;
  d: path("M4 14v-2h7v2zm0-4V8h11v2zm0-4V4h11v2zm9 14v-3.075l6.575-6.55l3.075 3.05L16.075 20zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
