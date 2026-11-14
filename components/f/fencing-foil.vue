<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2_3vfbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fencing-foil" /></template>
<style>
.d2_3vfbgl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.321 12.619L20.47 2.47q.052-.053.113-.094t.13-.069t.141-.043T21 2.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T21.75 3t-.057.287t-.163.243L11.381 13.679q.369.726.369 1.821q0 3.25-3.25 3.25q-1.095 0-1.821-.369L4.03 21.03q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l2.649-2.649q-.369-.726-.369-1.821q0-3.25 3.25-3.25q1.095 0 1.821.369");
}

</style>
