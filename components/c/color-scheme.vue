<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw7g_vrhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:color-scheme" /></template>
<style>
.gw7g_vrhf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 3.25q2.927 0 3.406 2.448q1.797-1.73 4.194-.051q2.427 1.699 1.361 4.014q.85-.055 1.68.332q1.314.613 1.81 1.976q1.196 3.287-2.091 4.485l-8.677 3.158q-.649.387-1.367.377q-1.39.186-2.303-.65q-1.1-.573-1.4-1.945q-.254-.67-.113-1.41V6.75q0-1.45 1.025-2.475T6.75 3.25m.01 12.5h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6 16.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
