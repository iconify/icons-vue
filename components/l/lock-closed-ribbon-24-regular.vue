<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onx1zi-po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-ribbon-24-regular" /></template>
<style>
.onx1zi-po {
  fill: currentColor;
  d: path("M21 22.3a.7.7 0 0 1-1.195.495L18.5 21.49l-1.305 1.305A.7.7 0 0 1 16 22.3v-3.058a4.5 4.5 0 0 0 2.5.758a4.5 4.5 0 0 0 2.5-.758zM12 1a5 5 0 0 1 5 5v2.01a3.25 3.25 0 0 1 3 3.24v.007A4.5 4.5 0 0 0 18.5 11h-.02a1.75 1.75 0 0 0-1.73-1.5h-9.5a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.784 1.75 1.75 1.75H15V22H7.25A3.25 3.25 0 0 1 4 18.75v-7.5a3.25 3.25 0 0 1 3-3.24V6a5 5 0 0 1 5-5m6.5 11a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M12 13.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M12 2.5A3.5 3.5 0 0 0 8.5 6v2h7V6A3.5 3.5 0 0 0 12 2.5");
}

</style>
