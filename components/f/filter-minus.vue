<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dibpowkru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:filter-minus" /></template>
<style>
.dibpowkru {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.399 3.25H7.101q-1.564 0-2.248 1.407t.282 2.637l2.901 3.693q.214.272.214.618v5.379q0 1.105.956 1.66t1.916.007l.868-.496q1.26-.72 1.26-2.171v-4.379q0-.346.214-.618l2.901-3.693q.966-1.23.282-2.637T14.399 3.25m6.601 14h-6q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 17.25");
}

</style>
