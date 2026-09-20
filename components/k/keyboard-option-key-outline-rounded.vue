<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmoo7kqet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-option-key-outline-rounded" /></template>
<style>
.lmoo7kqet {
  fill: currentColor;
  d: path("M15.925 19q-.55 0-1-.262T14.2 18L7.85 7H4q-.425 0-.712-.288T3 6t.288-.712T4 5h3.85q.55 0 1 .263T9.575 6l6.35 11H20q.425 0 .713.288T21 18t-.288.713T20 19zM16 7q-.425 0-.712-.288T15 6t.288-.712T16 5h4q.425 0 .713.288T21 6t-.288.713T20 7z");
}

</style>
