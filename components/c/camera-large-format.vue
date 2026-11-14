<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow5rre83n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-large-format" /></template>
<style>
.ow5rre83n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 3.75h-.5q-2.5 0-2.5 2.5v9.5q0 2.5 2.5 2.5h.5q1.852 0 2.332-1.372l9.937-2.485q.175.336.463.625q.732.732 1.768.732h.5q1.036 0 1.768-.732t.732-1.768v-4.5q0-1.036-.732-1.768T19.75 6.25h-.5q-1.036 0-1.768.732q-.288.289-.463.625L7.082 5.122Q6.602 3.75 4.75 3.75m6.5 3.961v6.578l-4 1V6.711zm1.5.375l4 1v3.828l-4 1zM22.25 21q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 21t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
