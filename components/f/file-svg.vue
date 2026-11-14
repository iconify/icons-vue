<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur0wl0biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-svg" /></template>
<style>
.ur0wl0biz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 2.75 2.75 2.75h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0 1.346-.952 2.298T17 22.25H7q-1.346 0-2.298-.952T3.75 19V5q0-1.346.952-2.298T7 1.75m7.25.75q0-.149-.057-.287t-.162-.243l5.999 6q-.105-.106-.243-.163T19.5 7.75h-4q-1.25 0-1.25-1.25zm3 9.25q0-2-2-2q-1.594 0-1.918 1.271q-4.758.303-5.061 5.061Q7 16.406 7 18q0 2 2 2t2-2q0-1.564-1.223-1.905q.289-3.308 3.622-3.572q.146.35.437.641q.586.586 1.414.586t1.414-.586t.586-1.414");
}

</style>
