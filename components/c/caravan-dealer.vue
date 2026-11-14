<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umqsrlbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caravan-dealer" /></template>
<style>
.umqsrlbyu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 8v8.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.438q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25H15q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V8q0-.17-.009-.332L20.75 9.98V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-11q0-.107-.03-.211q-.03-.103-.088-.193t-.139-.161t-.179-.116l-6.5-3q-.096-.045-.202-.061Q14.31 4.75 12.5 4.75H5q-1.346 0-2.298.952T1.75 8M7 7.75h1q2.25 0 2.25 2.25T8 12.25H7q-2.25 0-2.25-2.25T7 7.75");
}

</style>
