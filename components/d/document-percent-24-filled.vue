<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjhjydbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-percent-24-filled" /></template>
<style>
.fjhjydbct {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M12 8a2 2 0 0 0 2 2h6v10a2 2 0 0 1-2 2h-6.81A6.5 6.5 0 0 0 4 11.498V4a2 2 0 0 1 2-2h6zm-3 9.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m.33-2.828a.5.5 0 0 0-.707 0l-4.95 4.95a.5.5 0 0 0 .707.707l4.95-4.95a.5.5 0 0 0 0-.707M9 18.5a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1m-5-4a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m0 1a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1m15.5-7H14a.5.5 0 0 1-.5-.5V2.5z");
}

</style>
