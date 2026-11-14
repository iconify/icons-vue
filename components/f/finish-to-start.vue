<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji8uh3n1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:finish-to-start" /></template>
<style>
.ji8uh3n1s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3.25h-5q-3 0-3 3t3 3h5q2.598 0 2.946-2.25h2.054v6.689l-.47-.469q-.052-.053-.113-.094t-.13-.069t-.141-.043T13.75 13t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l.496.496q-2.466.254-2.466 2.974q0 1.243.879 2.121q.878.879 2.121.879h5q3 0 3-3t-3-3h-1.939l.469-.47q.106-.105.163-.243T18 13.75t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T17.25 13t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-.47.469V6.25q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15.5 5.5h-2.804q-.348-2.25-2.946-2.25");
}

</style>
