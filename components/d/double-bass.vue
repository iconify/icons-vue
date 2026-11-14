<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej07-uyfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:double-bass" /></template>
<style>
.ej07-uyfh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 5v4.275q2.228.155 3.069 1.275q.888 1.184.141 3.194q-.054.207.74.92q2.05 1.84 2.05 3.836q0 3.75-6.75 3.75T5.25 18.5q0-1.996 2.05-3.836q.794-.713.74-.92q-.747-2.01.141-3.194q.841-1.12 3.069-1.275V5.674q-1.5-.337-1.5-2.174q0-2.25 2.25-2.25t2.25 2.25q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.75-.75-.75t-.75.75t.75.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
