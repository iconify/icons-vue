<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh3-5veyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:feedback-outline-sharp" /></template>
<style>
.zh3-5veyl {
  fill: currentColor;
  d: path("M12 15q.425 0 .713-.288T13 14t-.288-.712T12 13t-.712.288T11 14t.288.713T12 15m-1-4h2V5h-2zM2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
