<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtro-by8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:earbud-right-rounded" /></template>
<style>
.gtro-by8s {
  fill: currentColor;
  d: path("M12 20V5q0-.425.288-.712T13 4h6q.825 0 1.413.588T21 6v4q0 .825-.587 1.413T19 12h-1v8q0 .825-.587 1.413T16 22h-2q-.825 0-1.412-.587T12 20M3 8q0-2.5 1.75-4.25T9 2q.425 0 .713.288T10 3v10q0 .425-.288.713T9 14q-2.5 0-4.25-1.75T3 8");
}

</style>
