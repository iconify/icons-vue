<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3gffoc6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:herbal-capsule" /></template>
<style>
.r3gffoc6k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.176 11.468q.974.318 1.756 1.1q1.318 1.318 1.318 3.182t-1.318 3.182t-3.182 1.318H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 11.25h3.08q-1.181-2.177-.28-4.519q1.223-3.179 5.566-3.969q.071-.013.143-.012t.142.015q.071.015.137.043t.127.067q.06.04.111.091t.092.109q.041.06.07.126t.044.136q1.249 5.619-2.056 8.131M12 11.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v7.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H6.25q-1.864 0-3.182-1.318T1.75 15.75t1.318-3.182T6.25 11.25z");
}

</style>
