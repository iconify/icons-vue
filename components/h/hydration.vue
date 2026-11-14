<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auk9a0bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hydration" /></template>
<style>
.auk9a0bom {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.479 2.21l-.019.019Q4.25 9.697 4.25 14.5q0 3.21 2.27 5.48T12 22.25t5.48-2.27t2.27-5.48q0-4.803-7.21-12.271q-.104-.107-.241-.167q-.137-.059-.286-.062t-.288.052t-.246.158m-1.424 14.235q.806.805 1.945.805q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-1.76 0-3.005-1.245T7.75 14.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 1.139.805 1.945");
}

</style>
