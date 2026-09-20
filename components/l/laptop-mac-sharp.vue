<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlxxx5k-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-mac-sharp" /></template>
<style>
.zlxxx5k-f {
  fill: currentColor;
  d: path("M0 20v-2h3l-1-1V3h20v14l-1 1h3v2zm12.713-1.287Q13 18.425 13 18t-.288-.712T12 17t-.712.288T11 18t.288.713T12 19t.713-.288");
}

</style>
