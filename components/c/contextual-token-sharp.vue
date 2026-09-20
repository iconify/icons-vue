<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ximgy8b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contextual-token-sharp" /></template>
<style>
.ximgy8b5z {
  fill: currentColor;
  d: path("M6 16h7v-3H6zm9 0h3V8h-3zm-9-5h7V8H6zm-4 9V4h20v16z");
}

</style>
