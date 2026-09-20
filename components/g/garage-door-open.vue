<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5veduxjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:garage-door-open" /></template>
<style>
.r5veduxjo {
  fill: currentColor;
  d: path("M8 12.5h8V11H8zM12 8q.425 0 .713-.288T13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8M4 20V10H.975L12 2l11 8h-3v10h-4v-6H8v6z");
}

</style>
