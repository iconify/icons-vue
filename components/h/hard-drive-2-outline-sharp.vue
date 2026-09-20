<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trsotdwtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hard-drive-2-outline-sharp" /></template>
<style>
.trsotdwtc {
  fill: currentColor;
  d: path("M14 19q.425 0 .713-.288T15 18t-.288-.712T14 17t-.712.288T13 18t.288.713T14 19m3 0q.425 0 .713-.288T18 18t-.288-.712T17 17t-.712.288T16 18t.288.713T17 19M3 13V2h18v11h-2V4H5v9zm2 2v5h14v-5zm-2 7v-9h18v9zm2-9h14zm0 2h14z");
}

</style>
