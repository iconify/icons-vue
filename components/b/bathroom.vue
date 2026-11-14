<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3mc0sied"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bathroom" /></template>
<style>
.p3mc0sied {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q2.25 0 2.25 2.25v4q0 2.25-2.25 2.25h-7q-2.25 0-2.25-2.25V4q0-2.25 2.25-2.25m7.75 12.5h4.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1q0 2.95-2.927 4.706Q15.749 22.25 12 22.25t-6.323-1.544Q2.75 18.95 2.75 16v-1q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h11.25v-1.5q0-.187-.562-.187q-.805 0-.992.466q-.027.068-.067.13t-.092.115t-.113.094t-.129.071t-.14.045t-.146.016t-.146-.013t-.142-.041q-.068-.027-.13-.067t-.115-.092t-.094-.113t-.071-.129t-.045-.14t-.016-.146t.013-.146t.041-.142q.563-1.408 2.384-1.408q2.062 0 2.062 1.687z");
}

</style>
