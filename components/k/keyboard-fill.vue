<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrzsflloy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyboard-fill" /></template>
<style>
.xrzsflloy {
  fill: currentColor;
  d: path("M5 4h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3m1 4a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm3 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm3.01 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M15 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm3.01 0H18a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M6 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm3.01 0H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm3.01 0H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M18 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-2 3H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
