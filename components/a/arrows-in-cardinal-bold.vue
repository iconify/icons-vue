<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gbphy3azn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-in-cardinal-bold" /></template>
<style>
.gbphy3azn {
  fill: currentColor;
  d: path("M87.51 72.49a12 12 0 0 1 17-17L116 67V24a12 12 0 0 1 24 0v43l11.51-11.52a12 12 0 0 1 17 17l-32 32a12 12 0 0 1-17 0Zm49 79a12 12 0 0 0-17 0l-32 32a12 12 0 0 0 17 17L116 189v43a12 12 0 0 0 24 0v-43l11.51 11.52a12 12 0 0 0 17-17ZM232 116h-43l11.52-11.51a12 12 0 0 0-17-17l-32 32a12 12 0 0 0 0 17l32 32a12 12 0 0 0 17-17L189 140h43a12 12 0 0 0 0-24m-127.51 3.51l-32-32a12 12 0 0 0-17 17L67 116H24a12 12 0 0 0 0 24h43l-11.49 11.51a12 12 0 0 0 17 17l32-32a12 12 0 0 0-.02-17");
}

</style>
