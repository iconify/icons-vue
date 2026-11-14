<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq70zgbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:avatar-name-tag" /></template>
<style>
.vq70zgbon {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 5q0-1.75.875-2.625T12 1.5q3.5 0 3.5 3.5T12 8.5T8.5 5M12 9.75q-6.25 0-6.25 4.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7.25 14q0-2.75 4.75-2.75T16.75 14q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.25-6.25-4.25M4.5 16h14.899q.956-.001 1.37.861t-.184 1.608l-.249.312q-.375.469 0 .937l.25.314q.597.745.183 1.607t-1.371.861H4.5q-2.25 0-2.25-2.25v-2q0-.932.659-1.591T4.5 16");
}

</style>
