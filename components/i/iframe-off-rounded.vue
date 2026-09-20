<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw4-vackn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:iframe-off-rounded" /></template>
<style>
.gw4-vackn {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4v2.85L1.35 4.2q-.3-.3-.288-.712t.313-.713t.713-.3t.712.3l18.375 18.4q.3.3.3.7t-.3.7t-.712.3t-.713-.3L17.15 20zm0-2h11.15l-10-10H4zM22 6v11q0 .5-.312.75T21 18t-.687-.262t-.313-.763V8h-8.325q-.4 0-.763-.15t-.637-.425L8.55 5.7q-.225-.25-.275-.525t.075-.55t.35-.45T9.275 4H20q.825 0 1.413.588T22 6m-4 5v1.725q0 .675-.612.938T16.3 13.45l-1.75-1.75q-.475-.475-.213-1.087t.938-.613H17q.425 0 .713.288T18 11");
}

</style>
