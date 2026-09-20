<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om4rwrhqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-info-sharp" /></template>
<style>
.om4rwrhqe {
  fill: currentColor;
  d: path("M12 7q.425 0 .713-.288T13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7m-1 8h2V9h-2zm-9 7V2h20v16H6z");
}

</style>
