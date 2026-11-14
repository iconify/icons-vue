<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4976lbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lungs" /></template>
<style>
.s4976lbpx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.25 8.712l-.5.556V8.5q0-.149-.057-.287t-.163-.243q-2.431-2.432-4.983-.014Q3.25 10.131 3.25 14.5q0 5.75 3.25 5.75q4.25 0 4.25-3.75v-4.99L12 10.121l1.25 1.389v4.99q0 3.75 4.25 3.75q3.25 0 3.25-5.75q0-4.369-2.297-6.544q-2.552-2.418-4.983.014q-.106.105-.163.243t-.057.287v.768l-.5-.556V3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 2.25 12 2.25t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 3z");
}

</style>
