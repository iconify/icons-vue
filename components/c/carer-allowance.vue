<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq6uzzbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carer-allowance" /></template>
<style>
.zq6uzzbve {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 3.25H6q-1.76 0-3.005 1.245T1.75 7.5v5q0 1.76 1.245 3.005T6 16.75h6.551q.206-1.086 1.035-1.914q1.957-1.957 3.914-1.039q1.675-.786 3.35.534q.4-.833.4-1.831v-5q0-1.76-1.245-3.005T17 3.25M8.25 10q0-1.347.951-2.299q.952-.952 2.299-.952t2.299.952T14.75 10q.001 1.346-.951 2.299t-2.299.952t-2.299-.952T8.25 10m8.72 11.78l-2.5-2.5q-.738-.737-.738-1.78t.738-1.78q1.515-1.515 3.03-.452q1.515-1.063 3.03.452q.738.737.738 1.78t-.738 1.78l-2.5 2.5q-.052.053-.113.094t-.13.069t-.141.043T17.5 22q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094m2.5-3.56l-1.97 1.969l-1.97-1.969q-.298-.298-.298-.72t.298-.72q.72-.719 1.44 0q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.72-.719 1.44 0q.298.298.298.72t-.298.72");
}

</style>
