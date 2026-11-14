<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7iircj2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:file-schema" /></template>
<style>
.s7iircj2j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h8.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V5q0 2.25 2.25 2.25h2.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0 1.346-.952 2.298T17 22.25H7q-1.346 0-2.298-.952T3.75 19V5q0-1.346.952-2.298T7 1.75m9.25.75q0-.149-.057-.287t-.163-.243l4 4q-.105-.106-.243-.163T19.5 5.75H17q-.75 0-.75-.75zm-7 3.75q-2.5 0-2.5 2.5v.5q0 1.036.732 1.768q.549.548 1.268.686V16.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.296q.138.719.686 1.268q.732.732 1.768.732h.5q1.036 0 1.768-.732t.732-1.768v-.5q0-2.5-2.5-2.5h-.5q-2.236 0-2.472 2H10.25v-4.046q.719-.138 1.268-.686q.732-.732.732-1.768v-.5q0-2.5-2.5-2.5z");
}

</style>
