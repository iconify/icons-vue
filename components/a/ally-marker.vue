<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6-eydbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ally-marker" /></template>
<style>
.r6-eydbll {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.493 22.053Q4 15.184 4 9.75q0-3.314 2.343-5.657T12 1.75t5.657 2.343T20 9.75q0 5.434-7.493 12.303q-.052.047-.111.084t-.124.062t-.134.038t-.138.013t-.138-.013t-.134-.038t-.124-.062t-.111-.084M12 4.75q-2.75 0-2.75 2.75T12 10.25t2.75-2.75T12 4.75m0 7q-3.25 0-3.25 3.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-1.75 1.75-1.75T13.75 15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.25-3.25-3.25");
}

</style>
