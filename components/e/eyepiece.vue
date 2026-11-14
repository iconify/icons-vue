<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1jm5qmyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyepiece" /></template>
<style>
.e1jm5qmyp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.204 1.75h7.592q1.316 0 1.937 1.16q.621 1.161-.109 2.256l-.98 1.471q-.179.269-.394.473V16q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.75v4.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-4.75H8.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 16V7.111q-.214-.205-.394-.474l-.98-1.471q-.73-1.095-.109-2.256t1.937-1.16m6.546 13.5V7.744q-.092.006-.187.006H9.437q-.095 0-.187-.005v7.505zm-1.5 5.5v-4h-2.5v4z");
}

</style>
