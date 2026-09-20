<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlu-acc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-content-rounded" /></template>
<style>
.jlu-acc6i {
  fill: currentColor;
  d: path("M7 17h3q.425 0 .713.288T11 18t-.288.713T10 19H6q-.425 0-.712-.288T5 18v-4q0-.425.288-.712T6 13t.713.288T7 14zM17 7h-3q-.425 0-.712-.288T13 6t.288-.712T14 5h4q.425 0 .713.288T19 6v4q0 .425-.288.713T18 11t-.712-.288T17 10z");
}

</style>
