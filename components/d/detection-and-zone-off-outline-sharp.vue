<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs19_uxll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detection-and-zone-off-outline-sharp" /></template>
<style>
.xs19_uxll {
  fill: currentColor;
  d: path("m21.11 22.58l-8.121-8.126l-.574 2.93h-3l1.039-5.33L7.5 13.273V16.5h-1v-3.892l3.285-1.352l-7.898-7.898l.713-.714l19.223 19.223zM3 21v-4h1v3h3v1zM20 7V4h-3V3h4v4zM3 7V4.039h1V7zm14 14v-1h2.962v1zM6.767 4l-1-1H7v1zM21 18.233l-1-1V17h1zm-7.5-9.04q-.71 0-1.201-.492T11.808 7.5t.491-1.201t1.201-.491t1.201.491t.491 1.201t-.491 1.201q-.492.491-1.201.491");
}

</style>
