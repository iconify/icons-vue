<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx4r9ku_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-letter-spacing-rounded" /></template>
<style>
.wx4r9ku_y {
  fill: currentColor;
  d: path("m7.825 19l.9.9q.275.275.275.688t-.3.712q-.275.275-.7.275t-.7-.275l-2.6-2.6q-.3-.3-.3-.7t.3-.7l2.6-2.6q.275-.275.688-.275t.712.275q.3.3.3.713t-.3.712L7.825 17h8.35l-.9-.9Q15 15.825 15 15.413t.3-.713q.275-.275.7-.275t.7.275l2.6 2.6q.3.3.3.7t-.3.7l-2.6 2.6q-.275.275-.687.275T15.3 21.3q-.3-.3-.3-.712t.3-.713l.875-.875zm-2.537-7.287Q5 11.425 5 11V3q0-.425.288-.712T6 2t.713.288T7 3v8q0 .425-.288.713T6 12t-.712-.288m6 0Q11 11.426 11 11V3q0-.425.288-.712T12 2t.713.288T13 3v8q0 .425-.288.713T12 12t-.712-.288m6 0Q17 11.426 17 11V3q0-.425.288-.712T18 2t.713.288T19 3v8q0 .425-.288.713T18 12t-.712-.288");
}

</style>
