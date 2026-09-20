<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="openekj_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-circle-28-filled" /></template>
<style>
.openekj_s {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12s-5.373 12-12 12S2 20.627 2 14S7.373 2 14 2m0 6a.75.75 0 0 0-.743.648l-.007.102v4.5h-4.5a.75.75 0 0 0-.102 1.493l.102.007h4.5v4.5a.75.75 0 0 0 1.493.102l.007-.102v-4.5h4.5a.75.75 0 0 0 .102-1.493l-.102-.007h-4.5v-4.5A.75.75 0 0 0 14 8");
}

</style>
