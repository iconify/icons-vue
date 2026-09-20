<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on1v3yb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitness-tracker" /></template>
<style>
.on1v3yb_r {
  fill: currentColor;
  d: path("m9 22l-1.2-3.975q-.375-.4-.587-.925T7 16V8q0-.6.213-1.125T7.8 5.95L9 2h6l1.15 3.925q.4.425.625.95T17 8v8q0 .6-.213 1.125t-.612.95L15 22zm1-5h4q.425 0 .713-.288T15 16V8q0-.425-.288-.712T14 7h-4q-.425 0-.712.288T9 8v8q0 .425.288.713T10 17");
}

</style>
