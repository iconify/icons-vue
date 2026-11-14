<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxs05wb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:for-here-mug" /></template>
<style>
.zxs05wb9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.25h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.25h.25q3.25 0 3.25 3.25t-3.25 3.25h-.25V13q0 2.081-.911 3.25H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .154-.061.295Q20.495 21.25 12 21.25q-8.493 0-10.189-3.953v-.002q-.059-.137-.061-.286V17q0-.144.054-.279q.055-.138.159-.245t.242-.165q.131-.057.274-.061h4.182Q5.75 15.081 5.75 13V4q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m10.75 8h.25q1.75 0 1.75-1.75T17.5 7.75h-.25zm-13.343 6.5q2.011 2 8.093 2t8.093-2z");
}

</style>
