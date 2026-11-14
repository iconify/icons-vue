<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpmvmabxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-search" /></template>
<style>
.tpmvmabxp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 6v12q0 3.25 3.25 3.25h9.661q-.587-.312-1.093-.818q-.324-.324-.569-.682H10.75V15.5h2.339q.329-.782.979-1.432l.069-.068H10.75V9.75h9.5v4.145q.092.083.182.173q1.318 1.318 1.318 3.182q0 .77-.225 1.447l.127.127q.098-.392.098-.824V6q0-1.346-.952-2.298T18.5 2.75h-13q-1.346 0-2.298.952T2.25 6m7 3.75V14h-5.5V9.75zm8 4.25Q14 14 14 17.25t3.25 3.25q1.095 0 1.821-.369l1.899 1.899q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.899-1.899q.369-.726.369-1.821q0-3.25-3.25-3.25m-8 1.5v4.25H5.5q-1.75 0-1.75-1.75v-2.5zm8 3.5q-1.75 0-1.75-1.75t1.75-1.75T19 17.25T17.25 19");
}

</style>
