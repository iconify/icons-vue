<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wot2b3dkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-off-20-filled" /></template>
<style>
.wot2b3dkp {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L13.293 14H12a.75.75 0 0 1-.183-1.476l-1.774-1.774H6.25a.75.75 0 0 1-.102-1.493l.102-.007h2.293L6.793 7.5H6a2.5 2.5 0 0 0-.164 4.995L6 12.5h2a.75.75 0 0 1 .102 1.493L8 14H6a4 4 0 0 1-.653-7.946l-3.2-3.2a.5.5 0 0 1 0-.707M14 6a4 4 0 0 1 1.727 7.607l-1.17-1.171a2.499 2.499 0 0 0-.393-4.931L14 7.5h-2a.75.75 0 0 1-.102-1.493L12 6zm-.25 3.25a.75.75 0 0 1 .102 1.493l-.102.007h-.879l-1.5-1.5z");
}

</style>
