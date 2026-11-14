<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d27wdebro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:farm-fleet" /></template>
<style>
.d27wdebro {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.5v5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.938q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h4.876q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V11q0-1.75-1.75-1.75h-.599l-2.777-4.166q-.051-.077-.12-.139q-.068-.063-.15-.106q-.082-.044-.172-.066T16.5 4.75H13q-1.75 0-1.75 1.75v3.25H9.8q.2-.459.2-1v-1q0-1.036-.732-1.768T7.5 5.25h-2Q3 5.25 3 7.75v1q0 .564.127 1H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146");
}

</style>
