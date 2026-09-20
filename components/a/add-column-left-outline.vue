<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzg72accn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-column-left-outline" /></template>
<style>
.fzg72accn {
  fill: currentColor;
  d: path("M20 19V5h-6v14zM4 21v-4h2v2h6V5H6v2H4V3h18v18zm10-9h-2zM4 15v-2H2v-2h2V9h2v2h2v2H6v2z");
}

</style>
