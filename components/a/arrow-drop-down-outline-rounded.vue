<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi9b2kjdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-drop-down-outline-rounded" /></template>
<style>
.qi9b2kjdk {
  fill: currentColor;
  d: path("m11.565 13.873l-2.677-2.677q-.055-.055-.093-.129q-.037-.073-.037-.157q0-.168.11-.289q.112-.121.294-.121h5.677q.181 0 .292.124t.111.288q0 .042-.13.284l-2.677 2.677q-.093.093-.2.143t-.235.05t-.235-.05t-.2-.143");
}

</style>
