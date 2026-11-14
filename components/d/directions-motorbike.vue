<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2_n00b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:directions-motorbike" /></template>
<style>
.b2_n00b9x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.479 11.269q.251-.019.521-.019q3.75 0 3.75 3.75T19 18.75T15.25 15q0-2.571 1.762-3.379L15.469 7.25H13.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014H16q.116 0 .227.035t.206.103t.165.16q.071.093.109.202zM7.357 9.614l-1.063 1.772Q5.715 11.25 5 11.25q-3.75 0-3.75 3.75T5 18.75q3.354 0 3.708-3H12.5q.112 0 .22-.033q.107-.033.2-.096t.164-.151t.112-.191l2-5q.054-.135.054-.279q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H8q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151");
}

</style>
