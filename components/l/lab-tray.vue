<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_wdeb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lab-tray" /></template>
<style>
.bk_wdeb0f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 12.75h1.5V6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6.8q.987.193 1.563 1.125q.726 1.175.108 2.411l-.766 1.532q-.692 1.383-2.237 1.382H6.082q-1.545.001-2.237-1.381l-.766-1.534q-.618-1.235.108-2.41q.576-.932 1.563-1.125V6q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-5 0h3.5v-6h-3.5zm8-6v6h3.5v-6z");
}

</style>
