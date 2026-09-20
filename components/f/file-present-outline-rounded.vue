<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnhthpx-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-present-outline-rounded" /></template>
<style>
.tnhthpx-n {
  fill: currentColor;
  d: path("M12 19q1.675 0 2.838-1.175T16 15v-3q0-.425-.288-.712T15 11t-.712.288T14 12v3q0 .825-.575 1.413T12 17q-.825 0-1.412-.587T10 15V9.5q0-.225.15-.363T10.5 9q.225 0 .363.138T11 9.5V14q0 .425.288.713T12 15t.713-.288T13 14V9.5q0-1.05-.725-1.775T10.5 7t-1.775.725T8 9.5V15q0 1.65 1.175 2.825T12 19m-6 3q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h9l5 5v13q0 .825-.587 1.413T18 22zm0-2h12V8h-3q-.425 0-.712-.288T14 7V4H6zM6 4v4zv16z");
}

</style>
