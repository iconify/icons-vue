<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8vhgdcmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lapel-pin" /></template>
<style>
.m8vhgdcmv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 8q0-1.968 1.391-3.359T16 3.25t3.359 1.391T20.75 8t-1.391 3.359T16 12.75q-1.581 0-2.791-.899l-3.764 3.765l.353.354q.586.585.586 1.414t-.586 1.414q-.585.586-1.414.586t-1.414-.586l-.354-.353L4.53 20.53q-.105.106-.243.163T4 20.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l2.085-2.086l-.353-.354q-.586-.585-.586-1.414t.586-1.414q.585-.586 1.414-.586t1.414.586l.354.353l3.765-3.764Q11.25 9.581 11.25 8");
}

</style>
