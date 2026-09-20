<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgdzerhph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dehaze-outline-rounded" /></template>
<style>
.fgdzerhph {
  fill: currentColor;
  d: path("M4 7q-.425 0-.712-.288T3 6t.288-.712T4 5h16q.425 0 .713.288T21 6t-.288.713T20 7zm0 12q-.425 0-.712-.288T3 18t.288-.712T4 17h16q.425 0 .713.288T21 18t-.288.713T20 19zm0-6q-.425 0-.712-.288T3 12t.288-.712T4 11h16q.425 0 .713.288T21 12t-.288.713T20 13z");
}

</style>
