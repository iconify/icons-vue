<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgh_2g5nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-open-outline-sharp" /></template>
<style>
.tgh_2g5nw {
  fill: currentColor;
  d: path("M11 13q.425 0 .713-.288T12 12t-.288-.712T11 11t-.712.288T10 12t.288.713T11 13m-4 8v-2l6-1V5.975L7 5V3l8 1.3v15.35zm-4 0v-2h2V3h14v16h2v2zm4-2h10V5H7z");
}

</style>
