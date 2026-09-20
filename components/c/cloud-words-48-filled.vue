<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df3q_wero"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-words-48-filled" /></template>
<style>
.df3q_wero {
  fill: currentColor;
  d: path("M12.041 20C12.55 13.84 17.71 9 24 9s11.45 4.84 11.959 11h.541a8.5 8.5 0 0 1 0 17h-25a8.5 8.5 0 0 1 0-17zm8.209-2a1.25 1.25 0 1 0 0 2.5h7.5a1.25 1.25 0 1 0 0-2.5zM10 28.75c0 .69.56 1.25 1.25 1.25h9.5a1.25 1.25 0 1 0 0-2.5h-9.5c-.69 0-1.25.56-1.25 1.25m17.25-1.25a1.25 1.25 0 1 0 0 2.5h9.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
