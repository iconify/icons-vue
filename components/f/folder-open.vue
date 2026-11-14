<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_7f8vb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-open" /></template>
<style>
.t_7f8vb-k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7v12q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T3.75 19v-.139q.718.889 1.916.889h11.435q1.641 0 2.294-1.506l1.733-4q.537-1.238-.204-2.366q-.466-.71-1.174-.973V9q0-2.75-2.75-2.75h-5.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25H5Q2.25 4.25 2.25 7m2.855 5.256L3.75 15.383V7q0-1.25 1.25-1.25h4.189l1.781 1.78q.105.106.243.163t.287.057H17q1.25 0 1.25 1.25v1.75H7.399q-1.641 0-2.294 1.506");
}

</style>
