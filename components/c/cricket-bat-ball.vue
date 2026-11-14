<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqaa-mbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cricket-bat-ball" /></template>
<style>
.zqaa-mbnt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 6q0-3.25 3.25-3.25T9.25 6T6 9.25T2.75 6m16.232-1.513l.531.531q2.386 2.386 0 4.772l-5.834 5.834q-2.25 2.25-4.5.257l-3.367 3.367q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l3.367-3.367q-1.993-2.25.257-4.5l5.834-5.834q2.386-2.386 4.772 0");
}

</style>
