<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcttooau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmarks-rounded" /></template>
<style>
.ikcttooau {
  fill: currentColor;
  d: path("m10 19l-4.55 2.275q-.5.25-.975-.038T4 20.376V8q0-.825.588-1.412T6 6h8q.825 0 1.413.588T16 8v12.375q0 .575-.475.863t-.975.037zm8.288-1.287Q18 17.425 18 17V4H8q-.425 0-.712-.288T7 3t.288-.712T8 2h10q.825 0 1.413.588T20 4v13q0 .425-.288.713T19 18t-.712-.288");
}

</style>
