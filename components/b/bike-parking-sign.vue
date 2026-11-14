<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9_q7ubly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-parking-sign" /></template>
<style>
.i9_q7ubly {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h12q1.76 0 3.005 1.245T22.25 6v8q0 1.76-1.245 3.005T18 18.25h-5.25v3.25q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-3.25H6q-1.76 0-3.005-1.245T1.75 14V6q0-1.76 1.245-3.005T6 1.75m4.098 8.252l.81-1.252h3.09l.287.698Q13 10.206 13 12.25q0 3.25 3.25 3.25t3.25-3.25T16.25 9q-.27 0-.518.022l-.538-1.308q-.043-.103-.113-.189t-.164-.148q-.092-.062-.199-.095q-.107-.032-.218-.032h-4q-.094 0-.185.023t-.173.068q-.083.045-.152.109t-.12.143L8.844 9.178q-.51-.179-1.094-.179q-1.347 0-2.299.952q-.951.952-.951 2.299t.951 2.299q.952.952 2.299.952t2.299-.952T11 12.25q.001-1.311-.902-2.248");
}

</style>
