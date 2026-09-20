<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su7-ytb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-flex-end-rounded" /></template>
<style>
.su7-ytb3g {
  fill: currentColor;
  d: path("M20.288 21.713Q20 21.425 20 21V3q0-.425.288-.712T21 2t.713.288T22 3v18q0 .425-.288.713T21 22t-.712-.288M15 17q-.425 0-.712-.288T14 16V8q0-.425.288-.712T15 7h1q.425 0 .713.288T17 8v8q0 .425-.288.713T16 17zm-6 0q-.425 0-.712-.288T8 16V8q0-.425.288-.712T9 7h1q.425 0 .713.288T11 8v8q0 .425-.288.713T10 17z");
}

</style>
