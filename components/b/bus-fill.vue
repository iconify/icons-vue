<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohg7s_btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-fill" /></template>
<style>
.ohg7s_btk {
  fill: currentColor;
  d: path("M20 17c0 1.27-.803 2.405-2 2.829V21a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1h-4v1a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 4 17V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3ZM17 4H7a1 1 0 0 0-1 1v7h12V5a1 1 0 0 0-1-1M9 5h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2M8 15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
