<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_1e8cbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:learn-and-earn" /></template>
<style>
.v_1e8cbnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.961 1.624q-.961-.455-1.922 0L5.551 4.216q-1.288.609-1.288 2.034t1.289 2.034l5.487 2.592q.961.455 1.922 0l5.488-2.592q1.288-.609 1.288-2.034t-1.289-2.034zM21.75 6.25v4.25q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V6.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T21 5.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M8.641 14.141Q7.25 15.532 7.25 17.5t1.391 3.359T12 22.25t3.359-1.391T16.75 17.5t-1.391-3.359T12 12.75t-3.359 1.391");
}

</style>
