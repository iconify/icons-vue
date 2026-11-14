<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toahy4bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fencer-en-garde" /></template>
<style>
.toahy4bow {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 6.939L3.28 2.22q-.052-.053-.113-.094t-.13-.069t-.141-.043T2.75 2t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2 2.676 2 2.75t.014.146q.015.073.043.141t.069.13t.094.113L6.939 8L4.22 10.72q-.011.01-.021.022q-.102.109-.153.249t-.045.29t.068.284t.173.236q1.582 1.459 3.735 1.416q1.767-.036 3.11-1.07l9.383 9.383q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-9.383-9.383q1.034-1.343 1.07-3.11q.043-2.153-1.416-3.735q-.01-.012-.021-.022q-.105-.106-.243-.163T11.25 4t-.287.057t-.243.163z");
}

</style>
