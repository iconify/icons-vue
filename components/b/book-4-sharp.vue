<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjnpitbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-4-sharp" /></template>
<style>
.sjnpitbth {
  fill: currentColor;
  d: path("M7 16h2V4H7zm-1 6q-1.25 0-2.125-.875T3 19V5q0-1.25.875-2.125T6 2h11v16H6q-.425 0-.712.288T5 19t.288.713T6 20h13V4h2v18z");
}

</style>
