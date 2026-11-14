<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2vgpccde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camp-pillow" /></template>
<style>
.u2vgpccde {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m21.03 4.97l-1.25-1.25q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l.719.72l-1.145 1.145q-7.515-2.362-15.031.143q-.088.03-.166.08q-.078.049-.142.117q-.063.067-.109.148q-.045.08-.07.17q-1.553 5.697 0 11.394q.025.09.07.17t.109.148t.142.117t.166.08q7.737 2.579 15.474 0q.088-.03.166-.08q.078-.049.142-.117q.063-.067.109-.148q.045-.08.07-.17q1.496-5.485.111-10.971L20.5 6.561l.72.719q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243z");
}

</style>
