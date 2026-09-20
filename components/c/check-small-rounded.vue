<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xun61pbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:check-small-rounded" /></template>
<style>
.xun61pbmm {
  fill: currentColor;
  d: path("m10 13.6l5.9-5.9q.275-.275.7-.275t.7.275t.275.7t-.275.7l-6.6 6.6q-.3.3-.7.3t-.7-.3l-2.6-2.6q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275z");
}

</style>
