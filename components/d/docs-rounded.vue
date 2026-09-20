<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu88wbtmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:docs-rounded" /></template>
<style>
.lu88wbtmr {
  fill: currentColor;
  d: path("M12 2v4q0 1.25.875 2.125T15 9h4v11q0 .825-.587 1.413T17 22H7q-.825 0-1.412-.587T5 20V4q0-.825.588-1.412T7 2zm2 0l5 5h-4q-.425 0-.712-.288T14 6zm-4 17h2q.425 0 .713-.288T13 18t-.288-.712T12 17h-2q-.425 0-.712.288T9 18t.288.713T10 19m0-4h4q.425 0 .713-.288T15 14t-.288-.712T14 13h-4q-.425 0-.712.288T9 14t.288.713T10 15");
}

</style>
