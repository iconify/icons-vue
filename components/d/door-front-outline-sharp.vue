<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcitzz90m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-front-outline-sharp" /></template>
<style>
.tcitzz90m {
  fill: currentColor;
  d: path("M3 21v-2h2V3h14v16h2v2zm4-2h10V5H7zm7-6q.425 0 .713-.288T15 12t-.288-.712T14 11t-.712.288T13 12t.288.713T14 13M7 5v14z");
}

</style>
