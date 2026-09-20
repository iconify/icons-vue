<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab3of2blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:earbud-right-outline" /></template>
<style>
.ab3of2blk {
  fill: currentColor;
  d: path("M14 22q-.825 0-1.412-.587T12 20v-8h-2v-2h4v10h2V10h3V6h-9V4h9q.825 0 1.413.588T21 6v4q0 .825-.587 1.413T19 12h-1v8q0 .825-.587 1.413T16 22zm-5-8q-2.5 0-4.25-1.75T3 8t1.75-4.25T9 2h1v12zm-1-2.125v-7.75q-1.35.35-2.175 1.425T5 8t.825 2.45T8 11.875M8 8");
}

</style>
