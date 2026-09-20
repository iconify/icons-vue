<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axap8bb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:forward-to-inbox-outline" /></template>
<style>
.axap8bb_t {
  fill: currentColor;
  d: path("M12 13L4 8v10h9v2H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v7h-2V8zm0-2l8-5H4zm7 12l-1.4-1.4l1.575-1.6H15v-2h4.175l-1.6-1.6L19 15l4 4zM4 8v11v-6v.075V6z");
}

</style>
