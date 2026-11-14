<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko7wni7cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-spot" /></template>
<style>
.ko7wni7cn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.252 18.687Q4.423 4.278 20.429 2.753q.073-.007.147.001q.073.007.144.029t.136.057t.122.082t.103.104t.082.123q.034.065.055.136q.022.07.029.144q.006.071 0 .142q-1.525 16.006-15.934 16.177L3.03 22.03q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113zM15.5 6.5q-2 0-2 2t2 2t2-2t-2-2m-4 7q0 2 2 2t2-2t-2-2t-2 2m-5 2q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
