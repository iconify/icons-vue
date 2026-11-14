<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxnn31jwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deposit-coin-bottle" /></template>
<style>
.rxnn31jwe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 1.75H13q3 0 3 3t-3 3h-1.5q-3 0-3-3t3-3m-.5 8V12q0 .761-1.102 1.699q-1.148.976-1.148 1.801V20q0 .75.75.75h5q.75 0 .75-.75v-4.5q0-.825-1.148-1.801Q13 12.761 13 12V9.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T13.75 9t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146V12q0 .068.574.556q1.676 1.426 1.676 2.944V20q0 2.25-2.25 2.25h-5q-2.25 0-2.25-2.25v-4.5q0-1.518 1.676-2.944q.574-.488.574-.556V9.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10.25 9t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
