<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elam3dbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kid-thumbs-up" /></template>
<style>
.elam3dbku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.914 10.25H8q-.145 0-.279.054q-.134.053-.239.153q-.512-.207-1.232-.207h-2q-2.5 0-2.5 2.5v7q0 1.036.732 1.768t1.768.732h2q.641 0 1.165-.28q.053.065.119.118t.142.088q.076.037.158.055T8 22.25h9.746q2.936.015 3.246-2.887l1.243-6.216q.015-.073.015-.147q0-3.25-3.25-3.25h-2.25V5.5q0-2.706-2.513-2.873q-2.437-.163-2.967 2.2zm10.836 5.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H13q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
