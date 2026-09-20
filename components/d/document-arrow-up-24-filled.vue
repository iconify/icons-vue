<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyj9azv7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-up-24-filled" /></template>
<style>
.wyj9azv7d {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M12 8a2 2 0 0 0 2 2h6v10a2 2 0 0 1-2 2h-6.812A6.5 6.5 0 0 0 4 11.498V4a2 2 0 0 1 2-2h6zm-5.146 6.147a.5.5 0 0 0-.708 0l-2.5 2.5a.5.5 0 1 0 .708.707L6 15.707V20.5a.5.5 0 0 0 1 0v-4.793l1.646 1.646a.5.5 0 1 0 .708-.707zM19.5 8.5H14a.5.5 0 0 1-.5-.5V2.5z");
}

</style>
