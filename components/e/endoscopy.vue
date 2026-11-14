<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egx2eyb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:endoscopy" /></template>
<style>
.egx2eyb2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 2.5v4.625l.3-.225q.568-.426 1.2-.68V9.5q0 2.409 2 3.522q.011 1.728 1.75 1.728q1.75 0 1.75-1.75t-1.75-1.75q-.768 0-1.199.337q-1.051-.723-1.051-2.087V5.868q1.372-.118 2.987.42Q20.25 7.626 20.25 12.5q0 3.959-2.817 6.438Q14.806 21.25 11 21.25q-3.207 0-5.248-1.814Q3.75 17.656 3.75 15q0-3.25 3.25-3.25q1.25 0 1.25-2.75q0-.087.02-.172t.059-.163q.039-.079.095-.146T8.55 8.4l.2-.15V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
