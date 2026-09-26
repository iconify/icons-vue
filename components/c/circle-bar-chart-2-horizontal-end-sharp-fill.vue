<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zzjf2zbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-2-horizontal-end-sharp-fill" /></template>
<style>
.zzjf2zbey {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM7 9L17 9L17 7L7 7L7 9ZM9.6667 13L17 13L17 11L9.6667 11L9.6667 13ZM12.3333 17L17 17L17 15L12.3333 15L12.3333 17Z");
}

</style>
