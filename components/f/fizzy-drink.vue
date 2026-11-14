<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqtxfyzhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fizzy-drink" /></template>
<style>
.yqtxfyzhc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 4q0-1.375.688-2.062q.687-.688 2.062-.688q2.75 0 2.75 2.75T15 6.75T12.25 4m-3.5-1.25Q6.5 2.75 6.5 5t2.25 2.25T11 5T8.75 2.75m1 6.25q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.228l2.326 2.792q.084.101.129.225q.045.123.045.255V20q0 2.25-2.25 2.25h-5q-2.25 0-2.25-2.25v-6.5q0-.132.045-.255q.045-.124.129-.225l2.326-2.792z");
}

</style>
