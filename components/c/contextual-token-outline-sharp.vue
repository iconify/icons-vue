<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0je-vb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contextual-token-outline-sharp" /></template>
<style>
.o0je-vb4s {
  fill: currentColor;
  d: path("M6 16h7v-3H6zm9 0h3V8h-3zm-9-5h7V8H6zm-2 7h16V6H4zm-2 2V4h20v16zm2-2V6z");
}

</style>
