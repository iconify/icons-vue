<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv751gbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:help-bulk-round" /></template>
<style>
.wv751gbui {
  fill: currentColor;
  d: path("M7.393 8.053A5.001 5.001 0 1 1 12 15a1.002 1.002 0 0 1-.866-1.5c.179-.309.509-.5.866-.5a3 3 0 1 0-3-3a1 1 0 0 1-2 0a5 5 0 0 1 .393-1.947M12.01 17a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
