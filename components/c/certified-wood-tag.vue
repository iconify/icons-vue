<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqergnbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:certified-wood-tag" /></template>
<style>
.cqergnbmw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q.149 0 .287.057t.243.163l3.5 3.5q.106.105.163.243T19.75 6v14q0 2.25-2.25 2.25h-11q-2.25 0-2.25-2.25V6q0-.149.057-.287t.163-.243l3.5-3.5q.105-.106.243-.163T8.5 1.75M12 4.5q-2.25 0-2.25 2.25T12 9t2.25-2.25T12 4.5m-1.029 11.411L9.03 13.97q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l2.5 2.5q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l.027-.028l4.5-5q.1-.111.15-.252q.05-.14.042-.289t-.072-.284t-.175-.234q-.055-.05-.119-.088q-.063-.037-.133-.062q-.069-.025-.143-.035t-.146-.007q-.074.004-.146.022q-.071.018-.138.05t-.126.076t-.108.099z");
}

</style>
