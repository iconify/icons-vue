<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7f95fipz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cosmetic-dropper" /></template>
<style>
.u7f95fipz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 7.75h-.25V5q0-2.25-2.25-2.25T9.75 5v2.75H9.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.194q-.814.372-1.499 1.057q-1.501 1.501-1.501 3.624v1.25q0 2.123 1.501 3.624t3.624 1.501h2.25q2.123 0 3.624-1.501t1.501-3.624v-1.25q0-2.123-1.501-3.624q-.685-.685-1.499-1.057V8.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M11.25 5v2.75h1.5V5q0-.75-.75-.75t-.75.75m-1 4.25h3.5v1.034q-.305-.034-.625-.034h-2.25q-.32 0-.625.034z");
}

</style>
