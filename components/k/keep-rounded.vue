<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofxalbb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keep-rounded" /></template>
<style>
.ofxalbb8q {
  fill: currentColor;
  d: path("M16 5v7l1.7 1.7q.15.15.225.338t.075.387V15q0 .425-.288.712T17 16h-4v5.85q0 .425-.288.713T12 22.85t-.712-.288T11 21.85V16H7q-.425 0-.712-.288T6 15v-.575q0-.2.075-.387T6.3 13.7L8 12V5q-.425 0-.712-.288T7 4t.288-.712T8 3h8q.425 0 .713.288T17 4t-.288.713T16 5");
}

</style>
