<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kng716jqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-square-rounded" /></template>
<style>
.kng716jqm {
  fill: currentColor;
  d: path("M12 17.5q-.425 0-.712-.288T11 16.5V13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h8V7.5q0-.425.288-.712T12 6.5h9q.425 0 .713.288T22 7.5v9q0 .425-.288.713T21 17.5z");
}

</style>
