<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1yw7hhdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:duck-head" /></template>
<style>
.w1yw7hhdt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.84 12.25q.228-3.467-2.399-5.974q-2.95-2.818-6.943-1.979q-3.993.838-5.562 4.603q-1.569 3.766.647 7.191q2.217 3.426 6.295 3.537q3.85.106 6.205-2.829q5.755.69 6.395-1.867q.009-.038.014-.076q.168-1.172-.319-1.854q-.537-.752-1.673-.752zm-5.83-3.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.75z");
}

</style>
