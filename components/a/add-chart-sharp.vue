<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne7ykh1nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-chart-sharp" /></template>
<style>
.ne7ykh1nx {
  fill: currentColor;
  d: path("M7 17h2v-7H7zm4 0h2V7h-2zm4 0h2v-4h-2zm2-8V7h-2V5h2V3h2v2h2v2h-2v2zM3 21V3h11v7h7v11z");
}

</style>
