<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxs31vbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-array-rounded" /></template>
<style>
.jxs31vbfp {
  fill: currentColor;
  d: path("M16 20q-.425 0-.712-.288T15 19t.288-.712T16 18h2V6h-2q-.425 0-.712-.288T15 5t.288-.712T16 4h2q.825 0 1.413.588T20 6v12q0 .825-.587 1.413T18 20zM6 20q-.825 0-1.412-.587T4 18V6q0-.825.588-1.412T6 4h2q.425 0 .713.288T9 5t-.288.713T8 6H6v12h2q.425 0 .713.288T9 19t-.288.713T8 20z");
}

</style>
