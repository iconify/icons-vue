<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzm06ubmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-double-arrow-up-outline-rounded" /></template>
<style>
.rzm06ubmp {
  fill: currentColor;
  d: path("M12 13.825L8.1 17.7q-.275.275-.687.288T6.7 17.7q-.275-.275-.275-.7t.275-.7l4.6-4.6q.15-.15.325-.213t.375-.062t.375.062t.325.213l4.6 4.6q.275.275.288.688t-.288.712q-.275.275-.7.275t-.7-.275zm0-6L8.1 11.7q-.275.275-.687.288T6.7 11.7q-.275-.275-.275-.7t.275-.7l4.6-4.6q.15-.15.325-.212T12 5.425t.375.063t.325.212l4.6 4.6q.275.275.288.688t-.288.712q-.275.275-.7.275t-.7-.275z");
}

</style>
