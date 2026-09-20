<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="altfxsb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hard-drive-outline-sharp" /></template>
<style>
.altfxsb0f {
  fill: currentColor;
  d: path("M4 16.423h16v-5.77H4zm13.822-2.178q.294-.293.294-.707t-.294-.706q-.293-.294-.706-.294q-.414 0-.707.294t-.293.706t.293.707t.707.293t.706-.293M21 9.654h-1.402l-2.423-2.5H6.825l-2.423 2.5H3l3.404-3.5h11.192zM3 17.423v-7.77h18v7.77z");
}

</style>
