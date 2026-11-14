<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgr-p1kby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:designer" /></template>
<style>
.xgr-p1kby {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.385 13.18l-3.499-5q-.053-.075-.086-.16t-.044-.176q-.012-.09-.001-.181t.043-.176l1.5-4q.04-.108.11-.198t.165-.155t.203-.1T10 3h4q.115 0 .224.034t.203.1q.094.065.165.155q.07.09.11.198l1.5 4q.032.085.043.176t-.001.181q-.011.091-.044.176t-.086.16l-3.499 5q.135-.194.135-.43V9q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 8.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 9v3.75q0 .236.135.43M12 14.75q-2.778 0-5.492 2.267Q6.013 16 4.5 16H4q-2.25 0-2.25 2.25v.5Q1.75 21 4 21h.5q2.217 0 2.25-2.184q5.25-5.041 10.5 0Q17.283 21 19.5 21h.5q2.25 0 2.25-2.25v-.5Q22.25 16 20 16h-.5q-1.513 0-2.008 1.017Q14.778 14.75 12 14.75");
}

</style>
