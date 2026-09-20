<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eql14yo-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eraser-size-1-sharp" /></template>
<style>
.eql14yo-u {
  fill: currentColor;
  d: path("M7 19q-.825 0-1.412-.587T5 17q0-.375.15-.737t.45-.663l10-10q.3-.3.663-.45T17 5q.825 0 1.413.587T19 7q0 .375-.137.75t-.438.675l-10 10q-.3.3-.663.438T7 19");
}

</style>
