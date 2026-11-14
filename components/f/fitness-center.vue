<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-6d5faoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fitness-center" /></template>
<style>
.l-6d5faoy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 10.25q0-2.5-2.5-2.5q-1.036 0-1.768.732q-.398.398-.579.885q-.185-.117-.403-.117q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v4q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.218 0 .403-.117q.181.487.579.885q.732.732 1.768.732t1.768-.732t.732-1.768v-1h8.5v1q0 1.036.732 1.768t1.768.732t1.768-.732q.398-.398.579-.885q.185.117.403.117q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.188 0-.353.088q-.404-1.588-2.397-1.588q-2.5 0-2.5 2.5v1h-8.5z");
}

</style>
