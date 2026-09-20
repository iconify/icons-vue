<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh1wcuwno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-usage-24-filled" /></template>
<style>
.mh1wcuwno {
  fill: currentColor;
  d: path("M18.25 2.996A2.75 2.75 0 0 1 21 5.746v12.5a2.75 2.75 0 0 1-2.75 2.75H5.75A2.75 2.75 0 0 1 3 18.246v-12.5a2.75 2.75 0 0 1 2.75-2.75zM7.75 9a.75.75 0 0 0-.75.747v6.507c0 .412.336.746.75.746s.75-.334.75-.746V9.746A.75.75 0 0 0 7.75 9m8.5-2a.74.74 0 0 0-.75.73v8.541c0 .403.336.73.75.73a.74.74 0 0 0 .75-.73V7.729a.74.74 0 0 0-.75-.73m-4.275 4.997a.73.73 0 0 0-.725.734l.035 3.547a.73.73 0 0 0 .74.72a.73.73 0 0 0 .725-.734l-.035-3.548a.73.73 0 0 0-.74-.719");
}

</style>
